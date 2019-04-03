**GESE DEPLOY Process - draft**

1. **Schedule the Deploy, **expectation is to plan it 24 hours before; a couple of hours will be enough is case the Deploy solves blockers (see next paragraph for instructions)

    1. To reschedule just press the Enable GESE button in the GESE <Platform> page and run the scheduler again.

2. **Align the Product Source code** with Platform source code.

**_Note : This first step is to be evaluated each time, because usually updates from platform need actions from HA side, they can be time consuming activities_**

Change the flow target of the your platform workspace to GESE Full Solution.

For example GESE.HAWasher:

![image alt text](image_0.png)![image alt text](image_1.png)

Check and evaluate ChangeSets one by one, if there are actions to be taken from the product side, eg. run sql queries or write source code.

To align the code : Accept specific changes sets coming from GESE Full Solution into GESE Platform and GESE <Target Platform> and merge any change in the GESE <Target Platform> component as required in that platform.

3. **Run GESE Kill - <Platform Specific> on MyApps**. 

That will kill users applications and disable the application in the database. Also, the GESE Status on the GESE Status web page [https://sites.google.com/a/whirlpool.com/eex-tools/tools/gese/gese-status](https://sites.google.com/a/whirlpool.com/eex-tools/tools/gese/gese-status) will be put in RED **_(todo: add the label)_**

Allow GESE Kill and wait for confirmation

4. Delete file **Keys.txt** file from the application server folder : 

**\\na.ad.whirlpool.com\xenapp\Applications\GESE\GESE_Washer_Integration**

*For GESE Washer only: **Application and Application1 both folder*

*If you cannot delete the** *Keys.txt file this means that not all users have been killed properly. Please go back to step 3 and run again the GESE Kill.

5. **DATABASE ALIGNMENT : **Compare the dev database with the production database and be sure that the database structure is the same using the Visual Studio component for database comparison

![image alt text](image_2.png)

Source database: the development database : **KZO-MSSQLD2.na.ad.whirlpool.com**

Target database: the production database : **Adc-mssqlp5.na.ad.whirlpool.com**

![image alt text](image_3.png)

Compare operation could get stuck due to very slow connection, in this case the server 

![image alt text](image_4.png)

Can be user through the Remote Desktop connection to run the compare and update

6. **Check database connection** : Be sure that the GESE application is using the production database checking the **..\WasherEditor\app.config** file at the <connectionStrings> tag

7. **VERSIONING : **Change the Assembly version and the File version in the startup project and the eeprom generator project.![image alt text](image_5.png)

and also in the Publish page in the startup project:

![image alt text](image_6.png)

Three files have to be changed and included in this check-in, select all them, right click and select Check-in and Associate Work Item.

The changes will be in the Assembly info file of the <application name>.Eeprom and in the startup project. I.e. Dryer.Eeprom and DryerEditor projects.

If you don’t see those changes do a Save All operation after the changes.

![image alt text](image_7.png)

8. **Create a track Build Item : **Click on Create New Work Item and Select a Track Build Item

![image alt text](image_8.png)

![image alt text](image_9.png)

On the Track build item fill the items:

* Summary: ‘<application name> version <version number>’; (i.e. GESE Dryer version 0.7.24.0)

* Filed Against: GESE/GESE <application>; (i.e. GESE/GESE Dryer)

* Owned by: <your user id>;

* Planned for: <current sprint/iteration>; (i.e. GESE Dryer Week 6)

![image alt text](image_10.png)

9. **Deliver the ChangeSet:  **Press ok and deliver the change sets.

10. **BUILD **: Open [IBM Rational Team Concert](https://jazz.net/downloads/rational-team-concert/releases/6.0.3/RTC-Client-Eclipse4.2-repo-6.0.3.zip) and, connecting to EES Modules SW Tools, **ask for a build** (you can also use the Visual Studio plug-in).

![image alt text](image_11.png)

After that the build is completed successfully, open the build details by double-clicking on the build.

![image alt text](image_12.png)

11. **Enable the GESE **: Enable  the Application in the Database changing the value in the table ApplicationLauncher column Enabled to True.

12. **Test : **Test the application in MyApps: execute the application from MyApps, verify the application version in the form title, try to generate the settings file associated to a project.

 

13. **Create a release** : In the latest build page click on the Create a release associate with this build:

![image alt text](image_13.png)

On the release name use the  ‘<application name> version <version number>’ pattern, i.e:

![image alt text](image_14.png)

Press OK then save this page.

Open the Releases page (Click Open on Architecture Tools node context menu in the tree on the left) and Archive the previous one:

![image alt text](image_15.png)

![image alt text](image_16.png)

14. **Send the email : **Write a New Post on the GESE HAWasher web page 

[https://sites.google.com/a/whirlpool.com/eex-tools/tools/gese/gese-ha-washer](https://sites.google.com/a/whirlpool.com/eex-tools/tools/gese/gese-ha-washer)

![image alt text](image_17.png)

In the title of the Post insert the GESE name and, if it is, the breaking changes label :

![image alt text](image_18.png)

Save the post and click Email Last Post.

This action will send the notification Email to all the subscriber and also, it will put the GESE Status as Green

**Schedule the Deploy**

Open the GESE Maintenance Scheduler application from Citrix : 

![image alt text](image_19.png)

![image alt text](image_20.png)

![image alt text](image_21.png)

**TroubleShooting**

Sometimes for unknown reasons can happen that the Citrix User Got stuck and the access to Citrix is denied.

GESE Kill or Deploy process is failing.

In this case ![image alt text](image_22.png)select the Log Off, wait 5-10 minutes and Log On again

Use the About, Connection Center to verify connections :

![image alt text](image_23.png)

Testing the GESE Deployed on Citrix :

![image alt text](image_24.png)

Please enter explorer : \\[na.ad.whirlpool.com](http://na.ad.whirlpool.com/)\xenapp\Applications\GESE

![image alt text](image_25.png)

Open the last build folder (or the previous one or 0.3.27.0) (maybe you need to unzip)

And the GESE_Washer_Integration folder

Compare the 2 WasherEditor.Exe.Config and change the current (latest version) inserting server paths wherever the automatic deploy failed

![image alt text](image_26.png)

