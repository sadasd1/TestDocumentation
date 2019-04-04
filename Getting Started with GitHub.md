## Tools-Team Documentation link:

[https://github.whirlpool.com/sadasd1/Tools-Team](https://github.whirlpool.com/sadasd1/Tools-Team)

## Forking?

A *fork* is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

### Propose changes to someone else's project

A great example of using forks to propose changes is for bug fixes. Rather than logging an issue for a bug you've found, you can:

* Fork the repository.

* Make the fix.

* Submit a *pull request* to the project owner.

If the project owner likes your work, they might pull your fix into the original repository!

### Use someone else's project as a starting point for your own idea.

At [the heart of open source](http://opensource.org/about) is the idea that by sharing code, we can make better, more reliable software.

When creating your public repository from a fork of someone's project, make sure to include a [license file](http://choosealicense.com/) that determines how you want your project to be shared with others.

For more information on open source, specifically how to create and grow an open source project, we've created [Open Source Guides](https://opensource.guide/) that will help you foster a healthy open source community by recommending best practices for creating and maintaining repositories for your open source project. You can also take a free [GitHub Learning Lab](https://lab.github.com/) course on maintaining open source communities.

## How to create a new folder in GitHub?

You cannot create an empty folder *and then* add files to that folder, but rather creation of a folder must happen *together with* adding of at least a single file. On github you can do it this way:

* go to the folder inside which you want to create another folder

* click on *New file*

* on the text field for the file name, first write the folder name you want to create

* **then type ****/**. This creates a folder

* you can add more folders similarly

* finally, give the new file a name, (eg. .gitkeep which is *[conventionall*y](https://stackoverflow.com/a/7229996) used to make git track otherwise empty folders, not a git feature though)

* finally click *Commit new file*.

![image alt text](image_0.png)

![image alt text](image_1.png)

![image alt text](image_2.png)

<table>
  <tr>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>Task.Delay(50).Wait();
                var result = _ntlLocal.SetForceReset(15, 50, NTL.OpcodesResultData.ResetMode.ENTER_IAP).GetAwaiter();
                _ntlLocal.Agent.EnterIAP(Parameters.NodeAddress);
                Task.Delay(500);
                Task.Run(async () => { this.IAPnodeInfo = await _ntlLocal.Agent.NodeInfoRequest(Parameters.NodeAddress); });
                Task.Delay(500).Wait();
                this.SoftwareVersion = this.IAPnodeInfo.SotwareVersion;
                this.Timeout = IAPnodeInfo.Timeout;
                RaisePropertyChangedEvent(() => this.Enabled);
                _ntlLocal.Agent.ExitIAP(Parameters.NodeAddress).GetAwaiter();
                SerialCommunicationSettings OldSerialCommunicationSettings = new SerialCommunicationSettings();
                IniFileHelper.Instance.Deserialize(OldSerialCommunicationSettings, MACConfigIni.COMM_PARAMS);
                _iBusDevice.SendCommand(80, new byte[] { 2, (byte)(OldSerialCommunicationSettings.Ccb2Node), 0 });
</td>
  </tr>
</table>


