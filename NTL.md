<?xml version="1.0"?>
<doc>
    <assembly>
        <name>NTL</name>
    </assembly>
    <members>
        <member name="T:NTL.APIWaitableMessages.API001WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.APIWaitableMessages.API001WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.APIWaitableMessages.API001WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.APIWaitableMessages.API001WaitableMessages.GetMaxPackage(System.String)">
            <summary>
            Gets the maximum package.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.APIWaitableMessages.API001WaitableMessages.GetRequestMaxPackage(System.String)">
            <summary>
            Gets the requestt maximum package.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.APIWaitableMessages.API001WaitableMessages.RevealAck(System.String,System.Byte,System.Byte)">
            <summary>
            Reveals the ack.
            </summary>
            <param name="id">The identifier.</param>
            <param name="api">The API.</param>
            <param name="opcode">The opcode.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.APIWaitableMessages.API001WaitableMessages.GetWakeUpAck(System.String,System.Byte)">
            <summary>
            Gets the wake up ack.
            </summary>
            <param name="id">The identifier.</param>
            <param name="source">The source.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.APIWaitableMessages.API009WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.APIWaitableMessages.API009WaitableMessages.GetPublishResetMessage(System.String)">
            <summary>
            Gets the publish reset message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.APIWaitableMessages.API220WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.APIWaitableMessages.API220WaitableMessages.FVTCommands">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.APIWaitableMessages.API220WaitableMessages.FVTCommands.START_FVT">
            <summary>
            The start FVT
            </summary>
        </member>
        <member name="F:NTL.APIWaitableMessages.API220WaitableMessages.FVTCommands.STOP_FVT">
            <summary>
            The stop FVT
            </summary>
        </member>
        <member name="F:NTL.APIWaitableMessages.API220WaitableMessages.FVTCommands.FVT_RESULTS">
            <summary>
            The FVT results
            </summary>
        </member>
        <member name="T:NTL.APIWaitableMessages.API220WaitableMessages.MCIErrorCommands">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.APIWaitableMessages.API220WaitableMessages.MCIErrorCommands.GET_ERROR_RESULTS">
            <summary>
            Read all errors from MCI and publishes
            </summary>
        </member>
        <member name="F:NTL.APIWaitableMessages.API220WaitableMessages.MCIErrorCommands.CLEAR_AND_GET_ERROR_RESULTS">
            <summary>
            Clear all errors from MCI, read and publish errors 
            </summary>
        </member>
        <member name="M:NTL.APIWaitableMessages.API220WaitableMessages.GetMotorFVTCommandWaitableMessage(System.String,NTL.APIWaitableMessages.API220WaitableMessages.FVTCommands,System.Byte)">
            <summary>
            Gets the motor FVT command waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="fvtCommand">The FVT command.</param>
            <param name="motorIndex">Index of the motor.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.APIWaitableMessages.API220WaitableMessages.GetMCIErrorCommandWaitableMessage(System.String,System.Byte)">
            <summary>
            Gets the door sensor command waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="motorIndex">Index of the motor.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API03WaitableMessages.API003WaitableMessages">
            <summary>
            ]
            
            </summary>
        </member>
        <member name="M:NTL.API03WaitableMessages.API003WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API03WaitableMessages.API003WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API03WaitableMessages.API003WaitableMessages.GetRevealNodesWaitableMessage(System.String)">
            <summary>
            Gets the reveal nodes waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API03WaitableMessages.API003WaitableMessages.GetRevealApisWaitableMessage(System.String)">
            <summary>
            Gets the reveal apis waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API03WaitableMessages.API003WaitableMessages.GetApiInfoWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets the API information waitable message.
            </summary>
            <param name="apiId">The API identifier.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API03WaitableMessages.API003WaitableMessages.GetInstanceInfoWaitableMessage(System.String)">
            <summary>
            Gets the instance information waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API05WaitableMessages.API005WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API05WaitableMessages.API005WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetLoadDataWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets the load data waitable message.
            </summary>
            <param name="loadID">The load identifier.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetLLIDataWaitableMessage(System.Byte,System.Byte,System.String)">
            <summary>
            Gets the lli data waitable message.
            </summary>
            <param name="lliType">Type of the lli.</param>
            <param name="lliPosition">The lli position.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetAllLLIDataWaitableMessage(System.String)">
            <summary>
            Gets all lli data waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetGIDataWaitableMessage(System.Byte,System.Byte,System.String)">
            <summary>
            Gets the gi data waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="giID">The gi identifier.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetAllLoadConfigurationWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets all load configuration waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetAllLLIConfigurationsWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets all lli configurations waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetAllGIConfigurationsWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets all gi configurations waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetHmiGIDataWaitableMessage(System.Byte,System.Byte,System.String)">
            <summary>
            Gets the hmi gi data waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="gi">The gi,is the byte with GI ReadType and GI Position (the same as the EVENT opcode 0x08).</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetHmiGIConfigurationsWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets the hmi gi configurations waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetHmiLLIDataWaitableMessage(System.Byte,System.Byte,System.Byte,System.String)">
            <summary>
            Gets the hmi lli data waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="lliType">Type of the lli.</param>
            <param name="lliPosition">The lli position.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetAllHmiLLIDataWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets all hmi lli data waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API05WaitableMessages.API005WaitableMessages.GetHmiLLIConfigurationsWaitableMessage(System.Byte,System.String)">
            <summary>
            Gets the hmi lli configurations waitable message.
            </summary>
            <param name="target">The target.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API07WaitableMessages.API007WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API07WaitableMessages.API007WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileInfo(System.String)">
            <summary>
            Gets the setting file information.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileData(System.String)">
            <summary>
            Gets the setting file data.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetFlashAlignment(System.String)">
            <summary>
            Gets the flash alignment.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetHMISettingFileData(System.String,System.Byte[])">
            <summary>
            Gets the hmi setting file data.
            </summary>
            <param name="id">The identifier.</param>
            <param name="offset">The offset.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileInfoById(System.String,System.Byte)">
            <summary>
            Gets the setting file information by Id.
            </summary>
            <param name="id">The identifier.</param>
            <param name="settingFileId">The setting file identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileDataById(System.String,System.Byte,System.Byte[],System.Byte[])">
            <summary>
            Gets the setting file data by identifier.
            </summary>
            <param name="id">The identifier.</param>
            <param name="settingFileId">The setting file identifier.</param>
            <param name="offset">The offset.</param>
            <param name="size">The size.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetRequestSettingFileDataById(System.String)">
            <summary>
            Gets the request setting file data by identifier.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetRequestSegmentInfo(System.String,System.Byte)">
            <summary>
            Gets the request segment information.
            </summary>
            <param name="id">The identifier.</param>
            <param name="segmentId">The segment identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetRequestSegmentData(System.String)">
            <summary>
            Gets the request segment data.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileDisplacementInfo(System.String,System.Int16,System.Int16)">
            <summary>
            Gets the setting file displacement information.
            </summary>
            <param name="id">The identifier.</param>
            <param name="pointerId">The pointer identifier.</param>
            <param name="displacement">The displacement.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetSettingFileDisplacementData(System.String,System.Int16,System.Int16,System.Int16,System.Byte)">
            <summary>
            Gets the setting file displacement data.
            </summary>
            <param name="id">The identifier.</param>
            <param name="pointerId">The pointer identifier.</param>
            <param name="displacement">The displacement.</param>
            <param name="offset">The offset.</param>
            <param name="displacementSize">Size of the displacement.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API07WaitableMessages.API007WaitableMessages.GetRequestSettingsFileInfoByID(System.String,System.Byte)">
            <summary>
            Gets the request settings file information by identifier.
            </summary>
            <param name="id">The identifier.</param>
            <param name="sectionId">The section identifier.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.API10WaitableMessages.API010WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API10WaitableMessages.API010WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.RequestSpecificVariableWaitableMessage(System.String,System.Byte)">
            <summary>
            Requests the specific variable waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="index">The index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.RequestFixedvariableWaitableMessage(System.String,System.Byte)">
            <summary>
            Requests the fixedvariable waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="index">The index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.RequestAllFixedvariableWaitableMessage(System.String)">
            <summary>
            Requests all fixedvariable waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.RequestAcquisitionConfigurationWaitableMessage(System.String)">
            <summary>
            Requests the acquisition configuration waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.RequestNumberOfVariablesWaitableMessage(System.String)">
            <summary>
            Requests the number of variables waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.VariableStreamWaitableMessage(System.String)">
            <summary>
            Variables the stream waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API10WaitableMessages.API010WaitableMessages.ChecksumWaitableMessage(System.String)">
            <summary>
            Checksums the waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API17WaitableMessages.API017WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API17WaitableMessages.API017WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API17WaitableMessages.API017WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API17WaitableMessages.API017WaitableMessages.GetTouchData(System.String,System.Byte,System.Byte,System.Byte)">
            <summary>
            Gets the publish reset message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="deviceId">The device identifier.</param>
            <param name="requestKeyId">The request key identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API0141WaitableMessages.API141WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API0141WaitableMessages.API141WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetLinkStatus(System.String,System.Byte)">
            <summary>
            Gets the link status.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetUniqueID(System.String,System.Byte)">
            <summary>
            Gets the unique identifier.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetAntennaRSSI(System.String,System.Byte,System.Byte)">
            <summary>
            Gets the antenna rssi.
            </summary>
            <param name="id">The identifier.</param>
            <param name="antennaId">The antenna identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetRegulatoryCode(System.String,System.Byte)">
            <summary>
            Gets the regulatory code.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetCurrentTxPower(System.String,System.Byte)">
            <summary>
            Gets the current tx power.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetAntennaPowerConfiguration(System.String,System.Byte)">
            <summary>
            Gets the antenna power configuration.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0141WaitableMessages.API141WaitableMessages.GetMACAddress(System.String,System.Byte)">
            <summary>
            Gets the mac address.
            </summary>
            <param name="id">The identifier.</param>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API0221WaitableMessages.API221WaitableMessages">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.API0221WaitableMessages.API221WaitableMessages"/> class.
            </summary>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetFailureFlagsWaitableMessage(System.String,System.Byte)">
            <summary>
            Getfailureflags waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="motorIndex">Index of the motor.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetMotorStatusWaitableMessage(System.String,System.Byte)">
            <summary>
            Get Motor status waitable message
            </summary>
            <param name="id">The identifier.</param>
            <param name="motorIndex">Index of the motor.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetAnalogDataWaitableMessage(System.String,System.Byte,System.Byte)">
            <summary>
            Get AnalogData waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="analogChannel">The analog channel.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetPeriodicDataStatusWaitableMessage(System.String)">
            <summary>
            GetPeriodicDataStatus waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetPeriodicAnalodDataWaitableMessage(System.String)">
            <summary>
            Gets the periodic analod data waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.API0221WaitableMessages.API221WaitableMessages.GetEventWaitableMessage(System.String,System.Byte)">
            <summary>
            Gets the event waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="MotorIndex">Index of the motor.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.CancellationTask">
            <summary>
            
            </summary>
        </member>
        <member name="P:NTL.CancellationTask.TokenSource">
            <summary>
            Gets or sets the token source.
            </summary>
            <value>
            The token source.
            </value>
        </member>
        <member name="P:NTL.CancellationTask.RunningTask">
            <summary>
            Gets or sets the running task.
            </summary>
            <value>
            The running task.
            </value>
        </member>
        <member name="M:NTL.CancellationTask.Wait">
            <summary>
            Waits this instance.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.CancellationTask.Run(System.Func{System.Threading.Tasks.Task})">
            <summary>
            Runs the specified action.
            </summary>
            <param name="action">The action.</param>
        </member>
        <member name="M:NTL.CancellationTask.Cancel(System.Boolean)">
            <summary>
            Cancels this instance.
            </summary>
            <returns></returns>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings">
            <summary>
            Current Device Message available strings
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.ACK">
            <summary>
            Acknowledge a received command
            <para>
            Message: "ACK"
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NACK">
            <summary>
            Not Acknowledge a received command
            <para>
            Message: "NACK: {0}"
            </para>
            {0} : reason
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BREAK">
            <summary>
            Break received in the Wide Bus
            <para>
            Message: "&lt;BREAK&gt;"
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ACK">
            <summary>
            Ack received in the Win Bus
            <para>
            Message: "&lt;ACK&gt;"
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NodeMode">
            <summary>
            Node Mode.
            <para>
            Message: "Node Mode: {0}, Func Mode: {1}, Address: {2}, Filter: {3}"
            </para>
            <para>
            {0} : Current Node mode "Sniffer, Simple Node, Arbiter or Service"
            {1} : Function Mode Byte, check FuncModeBits enum
            {2} : Current Device Address
            {3} : Filter - Extra info [obsolete]
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.Configuration">
            <summary>
            Configuration (Only in CCB2 Protocol)
            <para>
            Message: "Configuration: Protocol: {0}, Address: {1}, Node Mode: {2}, Poll List: {3}"
            </para>
            <para>
            {0} : Current WBOX Protocol "NONE, WIDE, WIN or WMSP"
            {1} : Current Device Address
            {2} : Current Node mode "Sniffer, Simple Node, Arbiter or Service"
            {3} : list of the Nodes in the Polling List in Hex and comma separated (ie. 01,0F)
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits">
            <summary>
            Func Mode bit position in the NodeMode message
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits.FILTER_ON">
            <summary>
            Bit 0 true if Filter is on
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits.CRC_ON">
            <summary>
            Bit 1 true if CRC check is on
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits.RAW_ON">
            <summary>
            Bit 2 true if Data is on
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits.TIMESTAMP_ON">
            <summary>
            Bit 3 true if Time Stamp is on (not used)
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.FuncModeBits.BROADCAST_FILTER_ON">
            <summary>
            Bit 4 true if Broadcast Filter is on
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.SoftwareVersion">
            <summary>
            Software Version
            <para>
            Message: "DLE Software Version: {0} {1}"
            </para>
            <para>
            {0} : Device Software version string - Old versions only contains 1 number, new versions contains 3 (i.e. n1,n2,n3)
            {1} : Device Hardware version string - CCB1 will be empty string, CCB2 versions contains 3 (i.e. n1,n2,n3)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NodeList">
            <summary>
            Current Node list set on the Device
            <para>
            Message: "Node List: {0}"
            </para>
            <para>
            {0} : list of the Nodes in the Node List in Hex and comma separated (ie. 01,0F)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.PollingList">
            <summary>
            Current Polling list set on the Device.
            <para>
            Message: "Polling List: {0}"
            </para>
            <para>
            {0} : list of the Nodes in the Polling List in Hex and comma separated (ie. 01,0F)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.Command">
            <summary>
            Command sent to Device
            <para>
            Message: "Command: {0}"
            </para>
            <para>
            {0} : Command sent to the device, 0x(Byte) if the command does not exist
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BrokenMessage">
            <summary>
            Reported Broken Message
            <para>
            Message: "Broken Message Protocol: {0}, Message: {1}"
            </para>
            <para>
            {0} : Protocol of the Broken Message (NONE, WIDE, WIN, WMSP)
            {1} : Data Bytes of the broken message in Hex and comma separated (ie. 01,0F)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.RepeatedMessage">
            <summary>
            Reported Repeated Message
            <para>
            Message: "Repeated Message: {0}"
            </para>
            <para>
            {0} : Simple Whirlpool Packet in Hex and comma separated (SOURCE, DESTINATION, SAP, DATA0..N)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.SerialResponseData">
            <summary>
            SerialResponse Data when the current port is Opened or closed
            <para>
            Message: "SerialResponseData: {0}"
            </para>
            <para>
            {0} : COM# OPEN or COM# Port closed
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.DataFlowState">
            <summary>
            Current Data Flow State
            <para>
            Message: "Data Flow: {0}"
            </para>
            <para>
            {0} : ON or OFF
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.DataFilterState">
            <summary>
            Current Data Filter State
            <para>
            Message: "Data Filter: {0}"
            </para>
            <para>
            {0} : ON or OFF
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BusStatus">
            <summary>
            Current Bus Status
            <para>
            Message: "Bus Status: {0}"
            </para>
            <para>
            {0} : list of the Nodes Statuses in <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NODE_STATUS"/> Enum string and comma separated (ie. PRESENT,PRESENT,NOT_PRESENT,...up to node14 )
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NODE_STATUS">
            <summary>
            Current enumeration of available node status
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NODE_STATUS.NOT_PRESENT">
            <summary>
            Node not present in the bus.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.NODE_STATUS.PRESENT">
            <summary>
            Node present in the bus.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KeyEvent">
            <summary>
            Key Event
            <para>
            Message: "Key Event: {0}"
            </para>
            <para>
            {0} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KEY_EVENT_LIST"/> enumeration. (i.e CLICK,HOLD,STUCK)
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KEY_EVENT_LIST">
            <summary>
            Current enumeration of available node status
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KEY_EVENT_LIST.CLICK">
            <summary>
            Key was clicked (pressed and released)
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KEY_EVENT_LIST.HOLD">
            <summary>
            Key Holded for 3 seconds.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.KEY_EVENT_LIST.STUCK">
            <summary>
            The key is stuck
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BusAttachmentState">
            <summary>
            Current Bus Attachment State
            <para>
            Message: "Bus Attachment State: {0}"
            </para>
            <para>
            {0} : True or False (true meaning Attached)
            </para>
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BusHardwareConnection">
            <summary>
            Current Bus Hardware Connection
            <para>
            Message: "Bus Hardware Connection: {0} Baud: {1}"
            </para>
            <para>
            {0} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION"/> enumeration (i.e. REGULAR_UART_TRANSLATOR, SERIAL_TX_RX_WITH_ECHO or SERIAL_TX_RX_WITHOUT_ECHO)
            {1} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE"/> enumeration (i.e. B9600..)
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION">
            <summary>
            Current enumeration of available hardware connections
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION.REGULAR_UART_TRANSLATOR">
            <summary>
            Regular 1 wire uart translator (Wide/Win driver) output
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION.SERIAL_TX_RX_WITH_ECHO">
            <summary>
            Serial Tx/Rx output expecting echo
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION.SERIAL_TX_RX_WITHOUT_ECHO">
            <summary>
            Serial Tx/Rx output skipping the echo check (used for IR connection)
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION.INVALID_CONNECTION">
            <summary>
            Invalid Connection
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE">
            <summary>
            Current enumeration of available hardware baud rate
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B1200">
            <summary>
            The B1200
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B2400">
            <summary>
            The B2400
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B4800">
            <summary>
            The B4800
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B9600">
            <summary>
            The B9600
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B19200">
            <summary>
            The B19200
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B38400">
            <summary>
            The B38400
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B57600">
            <summary>
            The B57600
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B115200">
            <summary>
            The B115200
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_BAUDRATE.B230400">
            <summary>
            The B230400
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BusHardwareTest">
            <summary>
            Current Bus Hardware Test State
            <para>
            Message: "Bus Hardware Test: {0} State: {1}"
            </para>
            <para>
            {0} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.HARDWARE_CONNECTION"/> enumeration (i.e. REGULAR_UART_TRANSLATOR, SERIAL_TX_RX_WITH_ECHO or SERIAL_TX_RX_WITHOUT_ECHO)
            {1} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE"/> enumeration (i.e. IDLE,SET_HIGH,...)
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE">
            <summary>
            Current enumeration of available bus hardware test state
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.IDLE">
            <summary>
            The idle
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.SET_HIGH">
            <summary>
            The set high
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.TEST_HIGH">
            <summary>
            The test high
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.TEST_LOW">
            <summary>
            The test low
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.TEST_PASS">
            <summary>
            The test pass
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUSHARDWARE_TEST_STATE_TYPE.TEST_FAIL">
            <summary>
            The test fail
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BusError">
            <summary>
            Bus Error. Reported when any error in the bus happen.
            <para>
            Message: "Bus Error: {0}"
            </para>
            <para>
            {0} : One of the enum items of <see cref="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR"/> enumeration.
            </para>
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR">
            <summary>
            Current enumeration of available Errors
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR.NO_ERROR">
            <summary>
            No error.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR.WIN_BUFFER_NOT_ALLOCATED">
            <summary>
            Win buffer not allocated.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR.WIN_INVALID_SIZE">
            <summary>
            Win message with an invalid size.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR.WIN_INVALID_ADDRESS">
            <summary>
            Win message with an invalid address.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.BUS_ERROR.WIN_FAIL">
            <summary>
            Win failure.
            </summary>
        </member>
        <member name="M:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.GetDeviceStringParameters(System.String,System.String)">
            <summary>
            Get the {#} from the Device Strings in a List of strings.
            </summary>
            <param name="devicestring">Device String Pattern (Constants from this class).</param>
            <param name="received_msg">Received message.</param>
            <returns>A list of strings with given parameters.</returns>
        </member>
        <member name="M:NTL.DeviceMessages.CCB2Commands.DeviceMessageStrings.CheckDeviceString(System.String,System.String)">
            <summary>
            Checks the if device string given match the device message received.
            </summary>
            <param name="devicestring">The device string to compare.</param>
            <param name="received_msg">The received message to be compared.</param>
            <returns><c>true</c> if the message is the given device string</returns>
        </member>
        <member name="T:NTL.DeviceMessages.DeviceMessageExtensions">
            <summary>
            Extends the DeviceMessage with service box unique needs.
            </summary>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageExtensions.ToJson(WhirlpoolCommunication.Packets.DeviceMessage)">
            <summary>
            To the json.
            </summary>
            <param name="dm">The device message.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.DeviceMessages.DeviceMessageHandler">
            <summary>
            Handler of Device Messages.
            </summary>
            <seealso cref="T:WhirlpoolCommunication.IMessageHandler" />
            <seealso cref="T:System.IDisposable" />
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.#ctor(WhirlpoolCommunication.IDevice)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.DeviceMessages.DeviceMessageHandler"/> class.
            </summary>
            <param name="device">The device.</param>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.SetLogger(WhirlpoolCommunication.Utilities.Logger.ILogger)">
            <summary>
            Sets the logger.
            </summary>
            <param name="logger">The logger.</param>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.Dispose">
            <summary>
            Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
            </summary>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="message">The message.</param>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.WaitDeviceMessage(NTL.DeviceMessages.WaitableDeviceMessage,System.Int32)">
            <summary>
            Waits a single device message.
            Returns null if timeout.
            </summary>
            <param name="message">The message.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.SendCommand(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sends the command.
            </summary>
            <param name="command">The command.</param>
            <param name="data">The data.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.DeviceMessages.DeviceMessageHandler.RequestCancellation">
            <summary>
            Requests the cancellation of wait messages.
            </summary>
            <returns></returns>
        </member>
        <member name="T:NTL.DeviceMessages.DeviceMessageResult">
            <summary>
            Result from a Device Message request.
            </summary>
        </member>
        <member name="P:NTL.DeviceMessages.DeviceMessageResult.ID">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.DeviceMessageResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.DeviceMessageResult.Message">
            <summary>
            Gets or sets the message.
            </summary>
            <value>
            The message.
            </value>
        </member>
        <member name="T:NTL.DeviceMessages.DeviceMessageRequestResult">
            <summary>
            Enumeration of device request results.
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.DeviceMessageRequestResult.ACK">
            <summary>
            The ack
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.DeviceMessageRequestResult.TIMEOUT">
            <summary>
            The timeout
            </summary>
        </member>
        <member name="F:NTL.DeviceMessages.DeviceMessageRequestResult.CANCELLED">
            <summary>
            The cancelled
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.ServiceBoxCommands.IServiceBoxPubCommand">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.DeviceMessages.ServiceBoxCommands.IServiceBoxPubCommand.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="message">The message.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateResultCommand">
            <summary>
            Parses a publish node update result.
            </summary>
            <seealso cref="T:NTL.DeviceMessages.ServiceBoxCommands.IServiceBoxPubCommand" />
        </member>
        <member name="F:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateResultCommand.pubNodeUpdateResult">
            <summary>
            The pub node update result
            </summary>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateResultCommand.ResultCode">
            <summary>
            Gets or sets the bytes written.
            </summary>
            <value>
            The bytes written.
            </value>
        </member>
        <member name="M:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateResultCommand.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="message">The message.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateResultCommand.PubNodeUpdateResult.ResultCode">
            <summary>
            The set bus configuration
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.DeviceMessages.ServiceBoxCommands.IServiceBoxPubCommand" />
        </member>
        <member name="F:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.pubNodeUpdateStatus">
            <summary>
            string to be sent to config bus
            </summary>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.EpochTimeCmdReceived">
            <summary>
            Gets or sets the epoch time command received.
            </summary>
            <value>
            The epoch time command received.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.DownloadCompleteOffest">
            <summary>
            Gets or sets the download complete offest.
            </summary>
            <value>
            The download complete offest.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.InstallationCompleteOffset">
            <summary>
            Gets or sets the installation complete offset.
            </summary>
            <value>
            The installation complete offset.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.BytesWritten">
            <summary>
            Gets or sets the bytes written.
            </summary>
            <value>
            The bytes written.
            </value>
        </member>
        <member name="M:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="message">The message.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="F:NTL.DeviceMessages.ServiceBoxCommands.PubNodeUpdateStatusCommand.PubNodeUpdateStatus.Status">
            <summary>
            The set bus configuration
            </summary>
        </member>
        <member name="T:NTL.DeviceMessages.WaitableDeviceMessage">
            <summary>
            Define a waitable device message.
            </summary>
            <seealso cref="T:NTL.WaitableMessage`1" />
        </member>
        <member name="P:NTL.DeviceMessages.WaitableDeviceMessage.Message">
            <summary>
            Gets or sets the message.
            It is a regular expression. Be carefull with special characters.
            </summary>
            <value>
            The message.
            </value>
        </member>
        <member name="P:NTL.DeviceMessages.WaitableDeviceMessage.Data">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.DeviceMessages.WaitableDeviceMessage.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.DeviceMessages.WaitableDeviceMessage" /> class.
            </summary>
            <param name="id">The identifier.</param>
        </member>
        <member name="M:NTL.DeviceMessages.WaitableDeviceMessage.CompareTo(WhirlpoolCommunication.Packets.DeviceMessage,System.Boolean)">
            <summary>
            Compares to the message incoming to the waitable message
            </summary>
            <param name="data">The data.</param>
            <param name="setMessageMatch">if set to <c>true</c> set message match if compare is true.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.DeviceMessages.WaitableDeviceMessage.Copy">
            <summary>
            Copies this instance.
            </summary>
            <returns></returns>
        </member>
        <member name="T:NTL.DeviceMessages.WaitableDeviceMessageQueue">
            <summary>
            Waitable reveal message queue
            </summary>
            <seealso cref="T:NTL.WaitableMessageQueue`1" />
        </member>
        <member name="M:NTL.DeviceMessages.WaitableDeviceMessageQueue.CompareTo(WhirlpoolCommunication.Packets.DeviceMessage)">
            <summary>
            Compares the incoming message against the queue.
            Returns true if the message
            </summary>
            <param name="incomingMessage">The incoming message.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.ByteArrayExtensions">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.ByteArrayExtensions.FixEndianess(System.Byte[],System.Boolean)">
            <summary>
            Fixes the endianess.
            </summary>
            <param name="data">The data.</param>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian].</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs">
            <summary>
            
            Setting file progress Args definition
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_UPDATE_IN_PROGRESS">
            <summary>
            The pa update in progress
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_UPDATE_SUCCESS">
            <summary>
            The pa update success
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_UPDATE_SUCCESS_REBOOT_NEEDED">
            <summary>
            The pa update success reboot needed
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_MEMORY_ALLOCATION">
            <summary>
            The pa error memory allocation
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_INVALID_INPUT">
            <summary>
            The pa error invalid input
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FAILED_RETRIEVING_FILE_FROM_SERVER">
            <summary>
            The pa error failed retrieving file from server
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_CRC_MISMATCH">
            <summary>
            The pa error CRC mismatch
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FAILED_BDF_PARSING">
            <summary>
            The pa error failed BDF parsing
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_WAIT_FOR_RESPONSE_TIMED_OUT">
            <summary>
            The pa error wait for response timed out
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FAILED_SENDING_MESSAGE">
            <summary>
            The pa error failed sending message
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_MODEL_DOES_NOT_MATCH">
            <summary>
            The pa error model does not match
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_INVALID_NODE">
            <summary>
            The pa error invalid node
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_NODE_IS_NOT_UPDATEABLE">
            <summary>
            The pa error node is not updateable
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_ECM_UPDATE_FAILED">
            <summary>
            The pa error ecm update failed
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_PART_NUMBER_MISMATCH">
            <summary>
            The pa error part number mismatch
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_MC200_UPDATE_FAILED_BUT_CONTINUE_UPDATE">
            <summary>
            The pa error m C200 update failed but continue update
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_NOT_ENOUGH_MEMORY_TO_DOWNLOAD_ALL_RESOURCES">
            <summary>
            The pa error not enough memory to download all resources
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_LENGTH_ERROR_IN_DESCRIPTOR_FILE">
            <summary>
            The pa error length error in descriptor file
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_POST_UPDATE_VERIFICATION_FAILED">
            <summary>
            The pa error post update verification failed
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FILETYPE_IS_NOT_SUPPORTED">
            <summary>
            The pa error filetype is not supported
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FILETYPE_REQUIRES_PROG_ADDR_IN_UBD">
            <summary>
            The pa error filetype requires prog addr in ubd
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_PROG_ADDR_NOT_IN_FIT_TABLE">
            <summary>
            The pa error prog addr not in fit table
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_PROG_END_ADDR_EXCEED_FIT_TABLE">
            <summary>
            The pa error prog end addr exceed fit table
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_NEED_APPLICATION_PERMISSION_BEFORE_UPDATE">
            <summary>
            The pa need application permission before update
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FILE_EXTENSION_NOT_SUPPORTED">
            <summary>
            The pa error file extension not supported
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FILE_EXTENSION_NOT_DSA">
            <summary>
            The pa error file extension not DSA
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_DSA_VERIFICATION_FAILED">
            <summary>
            The pa error DSA verification failed
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_APPLIANCE_PART_NUMBER_MISMATCH">
            <summary>
            The pa error appliance part number mismatch
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_UBD_GOT_CORRUPTED">
            <summary>
            The pa error ubd got corrupted
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_IAP_FAILURE">
            <summary>
            The pa error iap failure
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_RESTART_DURING_DOWNLOAD">
            <summary>
            The pa error restart during download
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_RESTART_WAITING_FOR_APPL_PERMISSION">
            <summary>
            The pa error restart waiting for appl permission
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_RESTART_DURING_IAP">
            <summary>
            The pa error restart during iap
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FAILED_UPDATING_WIFI_SW">
            <summary>
            The pa error failed updating wifi sw
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_FAILED_UPDATING_RADIO_SW">
            <summary>
            The pa error failed updating radio sw
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults.PA_ERROR_UNKNOWN">
            <summary>
            The pa error unknown
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.#ctor(System.Int32,System.Int32,System.Int32,System.Int32,NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.FirmwareUpdateResults)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs" /> class.
            </summary>
            <param name="epochTimeCmdReceived">The epoch time command received.</param>
            <param name="downloadCompleteOffest">The download complete offest.</param>
            <param name="installationCompleteOffset">The installation complete offset.</param>
            <param name="bytesWritten">The bytes written.</param>
            <param name="result">The result.</param>
        </member>
        <member name="P:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.EpochTimeCmdReceived">
            <summary>
            Gets or sets the epoch time command received.
            </summary>
            <value>
            The epoch time command received.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.DownloadCompleteOffest">
            <summary>
            Gets or sets the download complete offest.
            </summary>
            <value>
            The download complete offest.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.InstallationCompleteOffset">
            <summary>
            Gets or sets the installation complete offset.
            </summary>
            <value>
            The installation complete offset.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.BytesWritten">
            <summary>
            Gets or sets the bytes written.
            </summary>
            <value>
            The bytes written.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HttpFirmwareDownloadProgressArgs.Result">
            <summary>
            Gets or sets the result.
            </summary>
            <value>
            The result.
            </value>
        </member>
        <member name="T:NTL.OpcodesResultData.IHttpFirmwareDownloadProgress">
            <summary>
            Interface to implement the report progress.
            </summary>
            <seealso cref="T:System.IProgress`1" />
        </member>
        <member name="T:NTL.OpcodesResultData.PAEngineProgress">
            <summary>
            Provides the status, completion and ellapsed time of Setting file download process
            </summary>
            <seealso cref="T:ProgramAgentLib.IPAEngineProgress" />
        </member>
        <member name="P:NTL.OpcodesResultData.PAEngineProgress.Completion">
            <summary>
            Gets the completion percentage.
            </summary>
            <value>
            The completion percentage.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PAEngineProgress.Status">
            <summary>
            Gets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PAEngineProgress.EllapsedTime">
            <summary>
            Gets the ellapsed time.
            </summary>
            <value>
            The ellapsed time.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PAEngineProgress.State">
            <summary>
            Gets the state.
            </summary>
            <value>
            The state.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.PAEngineProgress.Report(ProgramAgentLib.PAEngineProgressArgs)">
            <summary>
            Reports the setting file download progress.
            </summary>
            <param name="value">The value.</param>
        </member>
        <member name="T:NTL.OpcodesResultData.ResetMode">
            <summary>
            Reset Mode enumeration.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.ResetMode.COLD">
            <summary>
            The cold
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.ResetMode.WARM">
            <summary>
            The warm
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.ResetMode.ENTER_IAP">
            <summary>
            The enter iap
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.EraseTypes">
            <summary>
            Firmware Erase types.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EraseTypes.BlockErase">
            <summary>
            The block erase.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EraseTypes.ChipErase">
            <summary>
            The chip erase.
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.NamespaceDoc">
            <summary>
            Provides definition of how to parse and present data for each Opcode of all APIs
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.RevealAck">
            <summary>
            Parses the payload of RevealACK
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.RevealAck.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealAck.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealAck.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealAck.ReasonCode">
            <summary>
            Gets or sets the reveal ack.
            </summary>
            <value>
            The reveal ack.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealAck.API">
            <summary>
            Gets or sets the API.
            </summary>
            <value>
            The API.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealAck.Opcode">
            <summary>
            Gets or sets the opcode.
            </summary>
            <value>
            The opcode.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.RevealAck.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetMaxMessageSize">
            <summary>
            Parsing the result for GetMaxmessageSize command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.GetMaxMessageSize.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMaxMessageSize.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
            [XmlIgnore]
        </member>
        <member name="P:NTL.OpcodesResultData.GetMaxMessageSize.MaxSendMessageSize">
            <summary>
            Gets or sets the size of the get maximum message.
            </summary>
            <value>
            The size of the get maximum message.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMaxMessageSize.MaxReceiveMessageSize">
            <summary>
            Gets or sets the maximum size of the receive message.
            </summary>
            <value>
            The maximum size of the receive message.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetMaxMessageSize.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.PublishWakeUpAckData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.PublishWakeUpAckData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishWakeUpAckData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishWakeUpAckData.Node">
            <summary>
            Gets or sets the node.
            </summary>
            <value>
            The nodes.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.PublishWakeUpAckData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.RevealNodes">
            <summary>
            Parses the result of RevealNodes command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.RevealNodes.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealNodes.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealNodes.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealNodes.Password">
            <summary>
            Gets or sets the password.
            </summary>
            <value>
            The password.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.RevealNodes.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.RevealApis">
            <summary>
            Parses the result of RevealAPIs command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.RevealApis.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealApis.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealApis.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RevealApis.ListOfAPIs">
            <summary>
            Gets or sets the apis.
            </summary>
            <value>
            The apis.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.RevealApis.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.ApiInfo">
            <summary>
            Parses the result of APIinfo command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.ApiInfo.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.ApiId">
            <summary>
            Gets or sets the API identifier.
            </summary>
            <value>
            The API identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.ApiType">
            <summary>
            Gets or sets the type of the API.
            </summary>
            <value>
            The type of the API.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.ApiVersion">
            <summary>
            Gets or sets the API version.
            </summary>
            <value>
            The API version.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApiInfo.ApiInstances">
            <summary>
            Gets or sets the API instances.
            </summary>
            <value>
            The API instances.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.ApiInfo.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.InstanceInfo">
            <summary>
            Parses the result of Ins command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.InstanceInfo.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.InstanceId">
            <summary>
            Gets or sets the instance identifier.
            </summary>
            <value>
            The instance identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.Type">
            <summary>
            Gets or sets the type.
            </summary>
            <value>
            The type.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.Version">
            <summary>
            Gets or sets the version.
            </summary>
            <value>
            The version.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.InstanceInfo.DescrChar">
            <summary>
            Gets or sets the description character.
            </summary>
            <value>
            The description character.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.InstanceInfo.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.TestCycles">
            <summary>
            Test Cycles enumeration to enable test cycles.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.TestCycles.EOL_TEST_0">
            <summary>
            The eol test 0
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.TestCycles.EOL_TEST_1">
            <summary>
            The eol test 1
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.TestCycles.EOL_TEST_2">
            <summary>
            The eol test 2
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.TestCycles.SERVICE_TEST_0">
            <summary>
            The service test 0
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.TestCycles.SERVICE_TEST_1">
            <summary>
            The service test 1
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.LoadData">
            <summary>
            Parses LoadData
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.LoadData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.LoadId">
            <summary>
            Gets or sets the load identifier.
            </summary>
            <value>
            The load identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.Consistency">
            <summary>
            Gets or sets the consistency.
            </summary>
            <value>
            The consistency.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.Status">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.DataSize">
            <summary>
            Gets or sets the size of the data.
            </summary>
            <value>
            The size of the data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LoadData.Data">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.LoadData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllLoadData">
            <summary>
            Parses All Load Data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllLoadData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadData.LoadAllData">
            <summary>
            Gets or sets the data information list.
            </summary>
            <value>
            The data information list.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllLoadData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.LLIData">
            <summary>
            Parses LLIData
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.LLIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.Type">
            <summary>
            Gets or sets the type.
            </summary>
            <value>
            The type.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.Position">
            <summary>
            Gets or sets the position.
            </summary>
            <value>
            The position.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.Status">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.DataSize">
            <summary>
            Gets or sets the size of the data.
            </summary>
            <value>
            The size of the data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.LLIData.Data">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.LLIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllLLIData">
            <summary>
            Parses All LLI data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllLLIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.AllLLIData.lliAllData">
            <summary>
            All LLI data
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIData.LLIallData">
            <summary>
            Gets or sets the ll iall data.
            </summary>
            <value>
            The ll iall data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllLLIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GIData">
            <summary>
            Parses GIData
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GIData.GIIndex">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GIData.ConvertedData">
            <summary>
            Gets or sets the converted data.
            </summary>
            <value>
            The converted data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.HmiGIData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.HmiGIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIData.GI">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            gi is the byte with GI ReadType and GI Position.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIData.DataSize">
            <summary>
            Gets or sets the size of the data.
            </summary>
            <value>
            The size of the data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIData.Data">
            <summary>
            Gets or sets the converted data.
            </summary>
            <value>
            The converted data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.HmiGIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllGIData">
            <summary>
            Parses ALL GI data 
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllGIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIData.GIallData">
            <summary>
            Gets or sets All GI data.
            </summary>
            <value>
            The g iall data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllGIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.HmiAllGIData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.HmiAllGIData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiAllGIData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiAllGIData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiAllGIData.HmiGIData">
            <summary>
            Gets or sets All GI data.
            </summary>
            <value>
            The HMI GI data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.HmiAllGIData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllLoadConfig">
            <summary>
            Parses AllLoadConfig data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllLoadConfig.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadConfig.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadConfig.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadConfig.LoadIds">
            <summary>
            Gets or sets the load identifier.
            </summary>
            <value>
            The load identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadConfig.PilotTypes">
            <summary>
            Gets or sets the consistency.
            </summary>
            <value>
            The consistency.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLoadConfig.NumberOfLoads">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllLoadConfig.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllLLIConfig">
            <summary>
            Parses AllLLIConfig data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllLLIConfig.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIConfig.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIConfig.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIConfig.LLiIds">
            <summary>
            Gets or sets the load identifier.
            </summary>
            <value>
            The load identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIConfig.LLiPositions">
            <summary>
            Gets or sets the consistency.
            </summary>
            <value>
            The consistency.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllLLIConfig.NumberOfLLis">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllLLIConfig.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllGIConfig">
            <summary>
            Parses ALLGICofig data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllGIConfig.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.GiIds">
            <summary>
            Gets or sets the GI ids.
            </summary>
            <value>
            The GI ids.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.LLiIds">
            <summary>
            Gets or sets the LLI ids.
            </summary>
            <value>
            The LLI ids.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.LLiPositions">
            <summary>
            Gets or sets the consistency.
            </summary>
            <value>
            The consistency.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllGIConfig.NumberOfGIs">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllGIConfig.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.HmiGIConfig">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.HmiGIConfig.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.HMINumberOfGIs">
            <summary>
            Gets or sets the number of GIs.
            </summary>
            <value>
            The number of GIs.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.HMITypeAndPostion">
            <summary>
            Gets or sets the type and postion.
            </summary>
            <value>
            The type and postion.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.HMIGiIds">
            <summary>
            Gets or sets the load identifier.
            </summary>
            <value>
            The load identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.HMILLiIds">
            <summary>
            Gets or sets the HMI LLI ids.
            </summary>
            <value>
            The HMI LLI ids.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HmiGIConfig.HMILLiPositions">
            <summary>
            Gets or sets the HMI LLI positions.
            </summary>
            <value>
            The HMI LLI positions.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.HmiGIConfig.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.EnumModeType">
            <summary>
            System mode enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumModeType.MODE_NORMAL">
            <summary>
            The mode normal
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumModeType.MODE_PROGRAMMING">
            <summary>
            The mode programming
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumModeType.MODE_BAD_SETTING_FILE">
            <summary>
            The mode bad setting file
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumModeType.MODE_LOWPOWER">
            <summary>
            The mode lowpower
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.EnumSubModeType">
            <summary>
            System submode enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumSubModeType.SUBMODE_NORMAL_INITIALIZE">
            <summary>
            for the first time in NORMAL SYSTEM MODE
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumSubModeType.SUBMODE_NORMAL_SUPERVISOR">
            <summary>
            Supervisor in control
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumSubModeType.SUBMODE_NORMAL_ERROR">
            <summary>
            The submode normal error
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumSubModeType.SUBMODE_NORMAL_EXT_CONTROL_ENTERING">
            <summary>
            change from PC To EXT
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnumSubModeType.SUBMODE_NORMAL_EXT_CONTROL_ENGAGED">
            <summary>
            The submode normal ext control engaged
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileInfo">
            <summary>
            Parses the payload of Setting file info command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileInfo.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.AcuCRC">
            <summary>
            Gets or sets the acu CRC.
            </summary>
            <value>
            The acu CRC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.AcuAddress">
            <summary>
            Gets or sets the acu address.
            </summary>
            <value>
            The acu address.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.AcuLength">
            <summary>
            Gets or sets the acu length.
            </summary>
            <value>
            The acu length.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.HmiCRC">
            <summary>
            Gets or sets the hmi CRC.
            </summary>
            <value>
            The hmi CRC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.HmiAddress">
            <summary>
            Gets or sets the hmi address.
            </summary>
            <value>
            The hmi address.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.HmiLength">
            <summary>
            Gets or sets the hmi length.
            </summary>
            <value>
            The hmi length.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.SettingFileAddress">
            <summary>
            Gets or sets the sf start.
            </summary>
            <value>
            The sf start.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.SettingFileLength">
            <summary>
            Gets or sets the size of the sf.
            </summary>
            <value>
            The size of the sf.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfo.SettingFileEndAddress">
            <summary>
            Gets or sets the sf end.
            </summary>
            <value>
            The sf end.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileInfo.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileInfoById">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileInfoById.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfoById.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfoById.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfoById.SettingFileId">
            <summary>
            Gets or sets the setting file identifier.
            </summary>
            <value>
            The setting file identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfoById.CRC">
            <summary>
            Gets or sets the CRC.
            </summary>
            <value>
            The CRC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileInfoById.Size">
            <summary>
            Gets or sets the size.
            </summary>
            <value>
            The size.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileInfoById.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileDataById">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileDataById.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDataById.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDataById.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDataById.SettingFileId">
            <summary>
            Gets or sets the setting file identifier.
            </summary>
            <value>
            The setting file identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDataById.Offset">
            <summary>
            Gets or sets the Offset.
            </summary>
            <value>
            Offset.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDataById.Data">
            <summary>
            Gets or sets the size.
            </summary>
            <value>
            The size.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileDataById.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileDisplacementInfo">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileDisplacementInfo.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.SettingFilePointer">
            <summary>
            Gets or sets the pointer identifier.
            </summary>
            <value>
            The pointer identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.SettingFileDisplacementId">
            <summary>
            Gets or sets the displacement.
            </summary>
            <value>
            The displacement.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.CRC">
            <summary>
            Gets or sets the displacement CRC.
            </summary>
            <value>
            The displacement CRC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementInfo.DisplacementSize">
            <summary>
            Gets or sets the size of the displacement.
            </summary>
            <value>
            The size of the displacement.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileDisplacementInfo.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileDisplacementData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileDisplacementData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.SettingFilePointer">
            <summary>
            Gets or sets the pointer identifier.
            </summary>
            <value>
            The pointer identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.SettingFileDisplacementId">
            <summary>
            Gets or sets the displacement.
            </summary>
            <value>
            The displacement.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.Offset">
            <summary>
            Gets or sets the index of the displacement.
            </summary>
            <value>
            The index of the displacement.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileDisplacementData.Data">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileDisplacementData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.HMISettingFileData">
            <summary>
            Parses the payload of SettingFileData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.HMISettingFileData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.HMISettingFileData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HMISettingFileData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HMISettingFileData.Offset">
            <summary>
            Gets or sets the offset.
            </summary>
            <value>
            The offset.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.HMISettingFileData.Data">
            <summary>
            Gets or sets the sf data.
            </summary>
            <value>
            The sf data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.HMISettingFileData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileFlashAlignment">
            <summary>
            Parses the payload of SettingFileFlashAlignment command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SettingFileFlashAlignment.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileFlashAlignment.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileFlashAlignment.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileFlashAlignment.FlashAlignment">
            <summary>
            Gets or sets the sf flash alignment.
            </summary>
            <value>
            The sf flash alignment.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileFlashAlignment.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.EnablePeriodicData">
            <summary>
            Enable periodic data enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnablePeriodicData.STOP">
            <summary>
            The off
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.EnablePeriodicData.START">
            <summary>
            The on
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SetExtractionEngineState">
            <summary>
            SetExtractionEngineState enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetExtractionEngineState.OFF">
            <summary>
            Extraction Engine state OFF
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetExtractionEngineState.ON">
            <summary>
            Extraction Engine state ON
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SetOnChange">
            <summary>
            SetOnChange enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetOnChange.OFF">
            <summary>
            The off
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetOnChange.ON">
            <summary>
            The on
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SetExtractionMethod">
            <summary>
            Set Extraction Method enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetExtractionMethod.REVEAL">
            <summary>
            Set Extraction Method as Reveal
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SetExtractionMethod.SPI">
            <summary>
            Set Extraction Method as SPI
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableStreamData">
            <summary>
            Parses Variable stream data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.IsLittleEndian">
            <summary>
            Gets or sets a value indicating whether this instance is little endian.
            </summary>
            <value>
            <c>true</c> if this instance is little endian; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.Checksum">
            <summary>
            Gets a value indicating whether this <see cref="T:NTL.OpcodesResultData.VariableStreamData"/> is checksum.
            </summary>
            <value>
              <c>true</c> if checksum; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.VariableInfoList">
            <summary>
            Gets or sets the variable information list.
            </summary>
            <value>
            The variable information list.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamData.VariableData">
            <summary>
            The variable data
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableStreamData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableStreamPacketList">
            <summary>
            
            </summary>
            <seealso cref="T:System.Collections.Generic.List`1" />
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacketList.StreamData">
            <summary>
            Gets the stream data.
            </summary>
            <value>
            The stream data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacketList.HasChecksum">
            <summary>
            Gets a value indicating whether this instance has checksum.
            </summary>
            <value>
              <c>true</c> if this instance has checksum; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacketList.IsValid">
            <summary>
            Returns true if the StreamData is valid.
            </summary>
            <value>
              <c>true</c> if this instance is valid; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableStreamPacket">
            <summary>
            
            </summary>
            <seealso cref="T:System.IComparable" />
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacket.StreamData">
            <summary>
            Gets the stream data.
            </summary>
            <value>
            The stream data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacket.FullStreamData">
            <summary>
            Gets the full stream data.
            </summary>
            <value>
            The full stream data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacket.StreamIndex">
            <summary>
            Gets or sets the index of the stream.
            </summary>
            <value>
            The index of the stream.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacket.Counter">
            <summary>
            Gets or sets the counter.
            </summary>
            <value>
            The counter.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableStreamPacket.Checksum">
            <summary>
            Gets or sets the checksum.
            </summary>
            <value>
            The checksum.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableStreamPacket.VariableStreamDataParser(WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Variables the stream data parser.
            </summary>
            <param name="incomingData">The incoming data.</param>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableStreamPacket.CompareTo(System.Object)">
            <summary>
            Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.
            </summary>
            <param name="obj">An object to compare with this instance.</param>
            <returns>
            A value that indicates the relative order of the objects being compared. The return value has these meanings: Value Meaning Less than zero This instance precedes <paramref name="obj" /> in the sort order. Zero This instance occurs in the same position in the sort order as <paramref name="obj" />. Greater than zero This instance follows <paramref name="obj" /> in the sort order.
            </returns>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableData">
            <summary>
            Variable stream data with its variable information
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableData.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.OpcodesResultData.VariableData"/> class.
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableData.#ctor(NTL.OpcodesResultData.VariableInfo,System.Double)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.OpcodesResultData.VariableData" /> class.
            </summary>
            <param name="variableInfo">The variable information.</param>
            <param name="data">The data.</param>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableData.#ctor(NTL.OpcodesResultData.VariableInfo,System.Byte[])">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.OpcodesResultData.VariableData"/> class.
            </summary>
            <param name="variableInfo">The variable information.</param>
            <param name="byteValue">The byte value.</param>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableData.Data">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableData.VariableInformation">
            <summary>
            Gets or sets the variable information.
            </summary>
            <value>
            The variable information.
            </value>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableDataTypes">
            <summary>
            Variable data types enumeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Byte">
            <summary>
            The byte
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.UInt16">
            <summary>
            The uint16
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.UInt32">
            <summary>
            The uint32
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.UInt64">
            <summary>
            The uint64
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.SByte">
            <summary>
            The sbyte
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Int16">
            <summary>
            The int16
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Int32">
            <summary>
            The int32
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Int64">
            <summary>
            The int64
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Single">
            <summary>
            The single
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Double">
            <summary>
            The double
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Array">
            <summary>
            The Array
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Regulation">
            <summary>
            The Regulation
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.Q15">
            <summary>
            The Q15.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.VariableDataTypes.TTE_Visualizer">
            <summary>
            The time to end visualizer type.
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableInfo">
            <summary>
            Variable information
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.Name">
            <summary>
            Gets or sets the name.
            </summary>
            <value>
            The name.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.Index">
            <summary>
            Gets or sets the index.
            </summary>
            <value>
            The index.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.Offset">
            <summary>
            Gets or sets the size of the array.
            </summary>
            <value>
            The size of the array.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.DataType">
            <summary>
            Gets or sets the type of the data.
            </summary>
            <value>
            The type of the data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.MemoryAddress">
            <summary>
            Gets or sets the memory address.
            </summary>
            <value>
            The memory address.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableInfo.VarSize">
            <summary>
            Gets the size of the variable.
            </summary>
            <value>
            The size of the variable.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableInfo.Clone">
            <summary>
            Clones this instance.
            </summary>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SpecificVariable">
            <summary>
            Parses specific variable data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.Index">
            <summary>
            Gets or sets the index.
            </summary>
            <value>
            The index.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.Value">
            <summary>
            Gets or sets the value array.
            </summary>
            <value>
            The value array.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.Bytes">
            <summary>
            The bytes
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.VariableDataType">
            <summary>
            Gets or sets the type of the variable data.
            </summary>
            <value>
            The type of the variable data.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.SpecificVariable.offset">
            <summary>
            The offset
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.Offset">
            <summary>
            Gets or sets the offset.
            </summary>
            <value>
            The offset.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.DataSize">
            <summary>
            Gets the size of the data.
            </summary>
            <value>
            The size of the data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SpecificVariable.IsLittleEndian">
            <summary>
            Gets a value indicating whether this instance is little endian.
            </summary>
            <value>
            <c>true</c> if this instance is little endian; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SpecificVariable.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.AcquisitionConfiguration">
            <summary>
            Parses the Acquisition configuration data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.Method">
            <summary>
            Gets or sets the index.
            </summary>
            <value>
            The index.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.MilliSecondPeriod">
            <summary>
            Gets or sets the value array.
            </summary>
            <value>
            The value array.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.BytesPerBitmap">
            <summary>
            Gets or sets the bytes per bitmap.
            </summary>
            <value>
            The bytes per bitmap.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.SelectedBitsLow">
            <summary>
            Gets or sets the selected bits lo.
            </summary>
            <value>
            The selected bits lo.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.SelectedBits">
            <summary>
            Gets or sets the selected bits.
            </summary>
            <value>
            The selected bits.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.SelectedBitsHigh">
            <summary>
            Gets or sets the selected bits hi.
            </summary>
            <value>
            The selected bits hi.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.OnChangeBitsLow">
            <summary>
            Gets or sets the on change bits lo.
            </summary>
            <value>
            The on change bits lo.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.OnChangeBits">
            <summary>
            Gets or sets the on change bits.
            </summary>
            <value>
            The on change bits.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AcquisitionConfiguration.OnChangeBitsHigh">
            <summary>
            Gets or sets the on change bits hi.
            </summary>
            <value>
            The on change bits hi.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AcquisitionConfiguration.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.NumberOfVariables">
            <summary>
            Parses the number of variables data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.NumberOfVariables.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.NumberOfVariables.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.NumberOfVariables.NumberOfFixedVariables">
            <summary>
            Gets or sets the number of fixedvariables.
            </summary>
            <value>
            The number of fixedvariables.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.NumberOfVariables.MaxNumberOfMemoryMappedVariables">
            <summary>
            Gets or sets the maximum number of memorymapped variables.
            </summary>
            <value>
            The maximum number of memorymapped variables.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.NumberOfVariables.NumberOfDefinedMemoryMappedVariables">
            <summary>
            Gets or sets the number of defined memory mapped variables.
            </summary>
            <value>
            The number of defined memory mapped variables.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.NumberOfVariables.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.FixedVariableMetadata">
            <summary>
            Parses the  fixed variable meta data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.Index">
            <summary>
            Gets or sets the index.
            </summary>
            <value>
            The index.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.NumberOfArrayElements">
            <summary>
            Gets or sets the numberof array elements.
            </summary>
            <value>
            The numberof array elements.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.ElementDataType">
            <summary>
            Gets or sets the type of the element data.
            </summary>
            <value>
            The type of the element data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FixedVariableMetadata.ConnectivityID">
            <summary>
            Gets or sets the connectivity identifier.
            </summary>
            <value>
            The connectivity identifier.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.FixedVariableMetadata.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllFixedVariableMetadata">
            <summary>
            Parses the  fixed variable meta data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.AllFixedVariableMetadata.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.AllFixedVariableMetadata.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllFixedVariableMetadata.VariablesMetadata">
            <summary>
            Gets or sets the variables metadata.
            </summary>
            <value>
            The variables metadata.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllFixedVariableMetadata.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.VariableMetadata">
            <summary>
            Class that represents the metadata of a variable.
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableMetadata.Index">
            <summary>
            Gets or sets the index.
            </summary>
            <value>
            The index.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableMetadata.NumberOfArrayElements">
            <summary>
            Gets or sets the numberof array elements.
            </summary>
            <value>
            The numberof array elements.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableMetadata.ElementDataType">
            <summary>
            Gets or sets the type of the element data.
            </summary>
            <value>
            The type of the element data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableMetadata.ConnectivityID">
            <summary>
            Gets or sets the connectivity identifier.
            </summary>
            <value>
            The connectivity identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.VariableMetadata.SizeOf">
            <summary>
            Gets the size of one Variable metadata in bytes.
            </summary>
            <value>
            The size of in bytes.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.VariableMetadata.ParseData(System.Byte[])">
            <summary>
            Parses the data.
            </summary>
            <param name="metadataBytes">The metadata bytes.</param>
        </member>
        <member name="T:NTL.OpcodesResultData.CheckSumData">
            <summary>
            Data from last packet of API10 Stream.
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.CheckSumData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="P:NTL.OpcodesResultData.CheckSumData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.CheckSumData.ChecksumData">
            <summary>
            The checksum data
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.CheckSumData.Counter">
            <summary>
            The counter
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.CheckSumData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.CycleNumberData">
            <summary>
            Parses Cycle number data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.CycleNumberData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNumberData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNumberData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNumberData.NumberOfCycles">
            <summary>
            Gets or sets the number of cycles.
            </summary>
            <value>
            The number.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.CycleNumberData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.StatusData">
            <summary>
            Parses Status data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.StatusData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusData.Status">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusData.ProductType">
            <summary>
            Gets or sets the type of the product.
            </summary>
            <value>
            The type of the product.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StatusData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.RegulationsData">
            <summary>
            Parses Regulations data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.RegulationsData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationsData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationsData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationsData.Regulations">
            <summary>
            Gets or sets the regulations.
            </summary>
            <value>
            The regulations.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationsData.ProductType">
            <summary>
            Gets or sets the type of the product.
            </summary>
            <value>
            The type of the product.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.RegulationsData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.StartRegulation">
             <summary>
             0 = Keep Current State
            1 = Submit Start
            2 = Reset Cycle
            3 = Pause
            4 = Reset Fault
            5 = Restart Condition
             </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.KEEP_CURRENT_STATE">
            <summary>
            The keep current state
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.SUBMIT_START">
            <summary>
            The submit start
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.RESET_CYCLE">
            <summary>
            The reset cycle
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.PAUSE">
            <summary>
            The pause
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.RESET_FAULT">
            <summary>
            The reset fault
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartRegulation.RESTART_CONDITION">
            <summary>
            The restart condition
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SystemMode">
            <summary>
            Parses system mode data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.SystemMode.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SystemMode.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SystemMode.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SystemMode.Mode">
            <summary>
            Gets or sets the mode.
            </summary>
            <value>
            The mode.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SystemMode.SubMode">
            <summary>
            Gets or sets the sub mode.
            </summary>
            <value>
            The sub mode.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SystemMode.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.RegulationById">
            <summary>
            Parses regulationsbyId data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.RegulationById.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationById.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationById.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationById.FunctionId">
            <summary>
            Gets or sets the function identifier.
            </summary>
            <value>
            The function identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.RegulationById.RegulationPosition">
            <summary>
            Gets or sets the regulation position.
            </summary>
            <value>
            The regulation position.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.RegulationById.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.StatusStructure">
            <summary>
            Parses statusstructure data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.StatusStructure.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusStructure.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusStructure.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusStructure.Structures">
            <summary>
            Gets or sets the structures.
            </summary>
            <value>
            The structures.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusStructure.StatusNoVaraibles">
            <summary>
            Gets or sets the status no varaibles.
            </summary>
            <value>
            The status no varaibles.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StatusStructure.RegulationPosition">
            <summary>
            Gets or sets the regulation position.
            </summary>
            <value>
            The regulation position.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StatusStructure.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.FunctionsId">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.FunctionsId.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FunctionsId.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FunctionsId.FunctionIdsInfo">
            <summary>
            Gets or sets the function ids information.
            </summary>
            <value>
            The function ids information.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.FunctionsId.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.FunctionIdInfos">
            <summary>
            
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FunctionIdInfos.FunctionIds">
            <summary>
            Gets or sets the function ids.
            </summary>
            <value>
            The function ids.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FunctionIdInfos.CompartmentNumber">
            <summary>
            The compartment number
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.CycleNames">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNames.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNames.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNames.CycleNamesInfo">
            <summary>
            Gets or sets the function ids information.
            </summary>
            <value>
            The function ids information.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.CycleNames.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.CycleNamesInfos">
            <summary>
            
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNamesInfos.CycleNamesInBytes">
            <summary>
            Gets or sets the cycle names in bytes.
            </summary>
            <value>
            The cycle names in bytes.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNamesInfos.CycleNames">
            <summary>
            Gets or sets the cycle names.
            </summary>
            <value>
            The cycle names.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CycleNamesInfos.CompartmentNumber">
            <summary>
            The compartment number
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.TouchData">
            <summary>
            Parses the result of Touch Data.
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.DeviceId">
            <summary>
            Gets or sets the index of the fault.
            </summary>
            <value>
            The index of the fault.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.RequestKeyId">
            <summary>
            Gets or sets the request key identifier.
            </summary>
            <value>
            The request key identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.KeyStatus">
            <summary>
            Gets or sets the key status.
            </summary>
            <value>
            The key status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.Raw">
            <summary>
            Gets or sets the raw data of the key.
            </summary>
            <value>
            The raw.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.Reference">
            <summary>
            Gets or sets the reference.
            </summary>
            <value>
            The reference.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.Threshold">
            <summary>
            Gets or sets the threshold.
            </summary>
            <value>
            The threshold.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.TouchData.Delta">
            <summary>
            Gets or sets the delta between Threshold and Raw.
            </summary>
            <value>
            The delta between Threshold and Raw.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.TouchData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the saved fault code.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.SavedFaultCode">
            <summary>
            Parses the result of Savedfaultcode command
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.SavedFaultCode.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.FaultIndex">
            <summary>
            Gets or sets the index of the fault.
            </summary>
            <value>
            The index of the fault.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.Code">
            <summary>
            Gets or sets the code.
            </summary>
            <value>
            The code.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.SubCode">
            <summary>
            Gets or sets the sub code.
            </summary>
            <value>
            The sub code.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SavedFaultCode.EngineeringCode">
            <summary>
            Gets or sets the engineering code.
            </summary>
            <value>
            The engineering code.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SavedFaultCode.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the saved fault code.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AllSavedFaultCodes">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AllSavedFaultCodes.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AllSavedFaultCodes.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllSavedFaultCodes.NumberOfFaults">
            <summary>
            Gets the number of faults.
            </summary>
            <value>
            The number of faults.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllSavedFaultCodes.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AllSavedFaultCodes.AllFaultCodes">
            <summary>
            Gets or sets all fault codes.
            </summary>
            <value>
            All fault codes.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.AllSavedFaultCodes.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.Statistics">
            <summary>
            Parses Statistics data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.Statistics.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.RequestedSection">
            <summary>
            Gets or sets the requested section bits.
            </summary>
            <value>
            The requested section bits.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.OffsetsToBuffer">
            <summary>
            Gets or sets the offsets to buffer.
            </summary>
            <value>
            The offsets to buffer.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.RequestedSectionsData">
            <summary>
            Gets or sets the requested sections data.
            </summary>
            <value>
            The requested sections data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.Statistics.Offset">
            <summary>
            Gets or sets the offset.
            </summary>
            <value>
            The offset.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.Statistics.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.DiagnosticConfig">
            <summary>
            Parses Diagnostic config data
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.DiagnosticConfig.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.DiagnosticConfig.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.DiagnosticConfig.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.DiagnosticConfig.DiagnosticConfigInfo">
            <summary>
            Gets or sets the diagnostic configuration information.The first byte of each pair is the number of blocks in the section. The second byte of each pair is the number of bytes in each block. 
            For example:Byte 1 = Number of data blocks in the 1st section
            Byte 2 = Size of a data block in the 1st section
            Byte 3 = Number of data blocks in the 2nd section
            Byte 4 = Size of a data block in the 2nd section etc.
            </summary>
            <value>
            The diagnostic configuration information.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.DiagnosticConfig.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.PlatformType">
            <summary>
            Platform type definition
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.HAwasher">
            <summary>
            The HA washer
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.VAwasher">
            <summary>
            The VA washer
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.Refrigeration">
            <summary>
            The refrigeration
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.Cooking">
            <summary>
            The cooking
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.Dryer">
            <summary>
            The dryer
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.Dishwasher">
            <summary>
            The dishwasher
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PlatformType.NotAvailable">
            <summary>
            The not available
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.DeviceType">
            <summary>
            API019 Device Type  definition
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.ACU">
            <summary>
            The acu
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.HMI">
            <summary>
            The hmi
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.MCU">
            <summary>
            The mcu
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.ExpansionACu">
            <summary>
            The expansion a cu
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.ExpansionHMI">
            <summary>
            The expansion hmi
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.ExpansionMCU">
            <summary>
            The expansion mcu
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.SettingFile">
            <summary>
            The setting file
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.DeviceType.NotAvailable">
            <summary>
            The not available
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.MicroVendorname">
            <summary>
            MicroVendor Name definition
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.Atmel">
            <summary>
            The atmel
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.Cypress">
            <summary>
            The cypress
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.FreeScale">
            <summary>
            The free scale
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.NXp">
            <summary>
            The n xp
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.Renesas">
            <summary>
            The renesas
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.ST">
            <summary>
            The st
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroVendorname.NotDefined">
            <summary>
            The not defined
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.ProductType">
            <summary>
            Product Type definition
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.ProductType.NotDefined">
            <summary>
            The not defined
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.MicroSpecific">
            <summary>
            API019 Micro Model type definition.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.SPECIFIC_NOT_DEFINED">
            <summary>
            The specific not defined
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ATMEL_MEGA">
            <summary>
            The atmel mega
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ATMEL_SAMD20">
            <summary>
            The atmel sam D20
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ATMEL_SAMD21">
            <summary>
            The atmel sam D21
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.NXP_MKE04Z128VLD4">
            <summary>
            The NXP mk e04 Z128 vl d4
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.NXP_MKE02Zxxx">
            <summary>
            The NXP mk e02 ZXXX
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.NXP_MKE14Zxxx">
            <summary>
            The NXP mk e14 ZXXX
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.NXP_MKV31xxx">
            <summary>
            The NXP mk V31XXX
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.NXP_MKV30xxx">
            <summary>
            The NXP mk V30XXX
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.RENESAS_RX210">
            <summary>
            The renesas r X210
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.RENESAS_RX130">
            <summary>
            The renesas r X130
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.RENESAS_RX24Txxx">
            <summary>
            The renesas r X24 TXXX
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.RENESAS_RS5X">
            <summary>
            The renesas r s5 x
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F0X">
            <summary>
            The st st M32 f0 x
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F100">
            <summary>
            The st st M32 F100
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F101">
            <summary>
            The st st M32 F101
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F103">
            <summary>
            The st st M32 F103
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F303">
            <summary>
            The st st M32 F303
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F40X">
            <summary>
            The st st M32 F40 x
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F41X">
            <summary>
            The st st M32 F41 x
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F42X">
            <summary>
            The st st M32 F42 x
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MicroSpecific.ST_STM32F43X">
            <summary>
            The st st M32 F43 x
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.ApplianceData">
            <summary>
            Parses the payload for getappliancedata command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.ApplianceData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.ApplianceData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApplianceData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApplianceData.ApplianceModelNumber">
            <summary>
            Gets or sets the appliance model number.
            </summary>
            <value>
            The appliance model number.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApplianceData.ApplianceSerialNumber">
            <summary>
            Gets or sets the appliance serial number.
            </summary>
            <value>
            The appliance serial number.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ApplianceData.NumberOfBoards">
            <summary>
            Gets or sets the number of boards.
            </summary>
            <value>
            The number of boards.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.ApplianceData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.BoardData">
            <summary>
            Parses the payload for BoardData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.BoardData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.BoardIndex">
            <summary>
            Gets or sets the index of the board.
            </summary>
            <value>
            The index of the board.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.PartNumber">
            <summary>
            Gets or sets the part number.
            </summary>
            <value>
            The part number.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.Revision">
            <summary>
            Gets or sets the revision.
            </summary>
            <value>
            The revision.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.SerialNumber">
            <summary>
            Gets or sets the serial number.
            </summary>
            <value>
            The serial number.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.BoardReplacement">
            <summary>
            Gets or sets the board replacement.
            </summary>
            <value>
            The board replacement.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.BoardData.BoardNumberofprojects">
            <summary>
            Gets or sets the board numberofprojects.
            </summary>
            <value>
            The board numberofprojects.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.BoardData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.ProjectData">
            <summary>
            Parses the payload for ProjectData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.ProjectData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.BoardIndex">
            <summary>
            Gets or sets the index of the board.
            </summary>
            <value>
            The index of the board.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProjectIndex">
            <summary>
            Gets or sets the index of the project.
            </summary>
            <value>
            The index of the project.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProjectName">
            <summary>
            Gets or sets the name of the project.
            </summary>
            <value>
            The name of the project.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProjectReleaseNumber">
            <summary>
            Gets or sets the project release number.
            </summary>
            <value>
            The project release number.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProjectReleaseDate">
            <summary>
            Gets or sets the project release date.
            </summary>
            <value>
            The project release date.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProjectReleaseRevision">
            <summary>
            Gets or sets the project release revision.
            </summary>
            <value>
            The project release revision.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.MicroVendor">
            <summary>
            Gets or sets the micro vendor.
            </summary>
            <value>
            The micro vendor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.MicroSpecific">
            <summary>
            Gets or sets the micro specific.
            </summary>
            <value>
            The micro specific.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.PlatformType">
            <summary>
            Gets or sets the type of the platform.
            </summary>
            <value>
            The type of the platform.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.DeviceType">
            <summary>
            Gets or sets the type of the device.
            </summary>
            <value>
            The type of the device.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProductConfigurationBitmap">
            <summary>
            Gets or sets the product configuration bitmap.
            </summary>
            <value>
            The product configuration bitmap.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ProductType">
            <summary>
            Gets or sets the type of the product.
            </summary>
            <value>
            The type of the product.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ClassBCRC">
            <summary>
            Gets or sets the class BCRC.
            </summary>
            <value>
            The class BCRC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ProjectData.ClassBID">
            <summary>
            Gets or sets the class bid.
            </summary>
            <value>
            The class bid.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.ProjectData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.ServiceData">
            <summary>
            Parses the payload for ServiceData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.ServiceData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.TestID">
            <summary>
            Gets or sets the test identifier.
            </summary>
            <value>
            The test identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.Testerversion">
            <summary>
            Gets or sets the testerversion.
            </summary>
            <value>
            The testerversion.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.TestDate">
            <summary>
            Gets or sets the test date.
            </summary>
            <value>
            The test date.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.TestAge">
            <summary>
            Gets or sets the test age.
            </summary>
            <value>
            The test age.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.TestDuration">
            <summary>
            Gets or sets the duration of the test.
            </summary>
            <value>
            The duration of the test.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ServiceData.TestResult">
            <summary>
            Gets or sets the test result.
            </summary>
            <value>
            The test result.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.ServiceData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.FVTData">
            <summary>
            Parses the payload for FVTData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.FVTData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.FVTIndex">
            <summary>
            Gets or sets the index of the FVT.
            </summary>
            <value>
            The index of the FVT.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.TesterID">
            <summary>
            Gets or sets the tester identifier.
            </summary>
            <value>
            The tester identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.TestVersion">
            <summary>
            Gets or sets the test version.
            </summary>
            <value>
            The test version.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.TestDate">
            <summary>
            Gets or sets the testdate.
            </summary>
            <value>
            The testdate.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FVTData.TestResult">
            <summary>
            Gets or sets the test result.
            </summary>
            <value>
            The test result.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.FVTData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.EOLData">
            <summary>
            Parses the payload for EOLData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.EOLData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.EOLIndex">
            <summary>
            Gets or sets the index of the eol.
            </summary>
            <value>
            The index of the eol.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.TesterID">
            <summary>
            Gets or sets the tester identifier.
            </summary>
            <value>
            The tester identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.TestVersion">
            <summary>
            Gets or sets the test version.
            </summary>
            <value>
            The test version.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.TestDate">
            <summary>
            Gets or sets the testdate.
            </summary>
            <value>
            The testdate.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.EOLData.TestResult">
            <summary>
            Gets or sets the test result.
            </summary>
            <value>
            The test result.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.EOLData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.CalibrationdData">
            <summary>
            Parses the payload for CalibrationdData command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.CalibrationdData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.CalibrationdData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CalibrationdData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CalibrationdData.CalibrationDataId">
            <summary>
            Gets or sets the calibration data identifier.
            </summary>
            <value>
            The calibration data identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.CalibrationdData.CalibrationData">
            <summary>
            Gets or sets the calibration data.
            </summary>
            <value>
            The calibration data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.CalibrationdData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.ClassBSignature">
            <summary>
            Parses the payload for ClassBSignature command
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.ClassBSignature.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.ClassBSignature.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ClassBSignature.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.ClassBSignature.ClassBSignatureData">
            <summary>
            Gets or sets the class b signature data.
            </summary>
            <value>
            The class b signature data.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.ClassBSignature.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetLinkStatus">
            <summary>
            Inform UI of link state 
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetLinkStatus.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetLinkStatus.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetLinkStatus.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetLinkStatus.LinkState">
            <summary>
            Gets or sets the state of the link.
            </summary>
            <value>
            The state of the link.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetLinkStatus.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetUniqueID">
            <summary>
            Inform UI of the SAID 
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetUniqueID.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetUniqueID.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetUniqueID.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetUniqueID.SAID">
            <summary>
            Gets or sets the SAID.
            </summary>
            <value>
            The said.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetUniqueID.UniqueId">
            <summary>
            Gets or sets the unique identifier.
            </summary>
            <value>
            The unique identifier.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetUniqueID.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AntennaRSSI">
            <summary>
            AntennaRSSI
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaRSSI.ANTENNA_A">
            <summary>
            0 for antenna A
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaRSSI.ANTENNA_B">
            <summary>
            1 for antenna b
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaRSSI.ANTENNA_C">
            <summary>
            2 for antenna C
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.GetAntennaRSSI">
            <summary>
            GetAntennaRSSI
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetAntennaRSSI.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaRSSI.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaRSSI.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaRSSI.AntennaId">
            <summary>
            Gets or sets the antenna identifier.
            </summary>
            <value>
            The antenna identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaRSSI.RSSI">
            <summary>
            Gets or sets the rssi.
            </summary>
            <value>
            The rssi.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetAntennaRSSI.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetRegulatoryCode">
            <summary>
            GetRegulatoryCode
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetRegulatoryCode.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetRegulatoryCode.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetRegulatoryCode.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetRegulatoryCode.RegulatoryCode">
            <summary>
            Gets or sets the regulatory code.
            </summary>
            <value>
            The regulatory code.
            </value>
        </member>
        <member name="T:NTL.OpcodesResultData.GetRegulatoryCode.RegulatoryCodeEnum">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.GetRegulatoryCode.RegulatoryCodeEnum.US">
            <summary>
            The us
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.GetRegulatoryCode.RegulatoryCodeEnum.EU">
            <summary>
            The eu
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.GetRegulatoryCode.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetCurrentTxPower">
            <summary>
            GetCurrentTxPower
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetCurrentTxPower.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetCurrentTxPower.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetCurrentTxPower.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetCurrentTxPower.DataRate">
            <summary>
            Gets or sets the data rate.
            </summary>
            <value>
            The data rate.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetCurrentTxPower.Power">
            <summary>
            Gets or sets the power.
            </summary>
            <value>
            The power.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetCurrentTxPower.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AntennaPowerConfig">
            <summary>
            AntennaPowerConfig
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.UNSET">
            <summary>
            The unset
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.ONBOARD">
            <summary>
            The onboard
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.PIFA">
            <summary>
            The pifa
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.F">
            <summary>
            The f
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.SLOT">
            <summary>
            The slot
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaPowerConfig.DIPOLE">
            <summary>
            The dipole
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.AntennaConfig">
            <summary>
            AntennaConfig
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaConfig.ONBOARD_ONBOARD">
            <summary>
            The onboard/ onboard
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaConfig.ONBOARD_OFFBOARD">
            <summary>
            The onboard/ offboard
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaConfig.OFFBOARD_ONBOARD">
            <summary>
            The offboard/ onboard
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.AntennaConfig.OFFBOARD_OFFBOARD">
            <summary>
            The offboard/ offboard
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.GetAntennaPowerConfiguration">
            <summary>
            GetAntennaPowerConfiguration
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetAntennaPowerConfiguration.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaPowerConfiguration.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaPowerConfiguration.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaPowerConfiguration.AntennaAPowerConfig">
            <summary>
            Gets or sets the data rate.
            </summary>
            <value>
            The data rate.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetAntennaPowerConfiguration.AntennaBPowerConfig">
            <summary>
            Gets or sets the power.
            </summary>
            <value>
            The power.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetAntennaPowerConfiguration.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.GetMacAddress">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.GetMacAddress.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMacAddress.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMacAddress.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMacAddress.MacAddress">
            <summary>
            Gets or sets the mac address.
            </summary>
            <value>
            The mac address.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMacAddress.MAC">
            <summary>
            Gets or sets the unique identifier.
            </summary>
            <value>
            The unique identifier.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetMacAddress.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.StartMotorFVTErrorCodes">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_INDEX_OUT_RANGE">
            <summary>
            The mci command index out range
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_STOP_REQUESTED">
            <summary>
            The mci command stop requested
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_PARAM_NOT_LOADED">
            <summary>
            The mci command parameter not loaded
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_TIMEOUT">
            <summary>
            The mci command timeout
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_RAMP_OUT_OF_RANGE">
            <summary>
            The mci command ramp out of range
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_SPEED_OUT_OF_RANGE">
            <summary>
            The mci command speed out of range
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_DENIED">
            <summary>
            The mci command denied
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StartMotorFVTErrorCodes.MCI_CMD_ACCEPTED">
            <summary>
            The mci command accepted
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.MotorFVTConstants">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MotorFVTConstants.Volts">
            <summary>
            The volts
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MotorFVTConstants.Amperes">
            <summary>
            The amperes
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MotorFVTConstants.MinimumMotorFVTGetResults">
            <summary>
            The minimum motor FVT get results
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MotorFVTConstants.MinimumMotorFVTCommandResults">
            <summary>
            The minimum motor FVT command results
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.MotorFVTConstants.MinimumMCIErrorResults">
            <summary>
            The minimum mci error results
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.StartMotorFVTResult">
            <summary>
            Parse the Start Motor FVT results.
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.StartMotorFVTResult.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartMotorFVTResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartMotorFVTResult.Error">
            <summary>
            Gets or sets the error.
            </summary>
            <value>
            The error.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartMotorFVTResult.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StartMotorFVTResult.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.StopMotorFVTResult">
            <summary>
            Parse the Stop Motor FVT results.
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="T:NTL.OpcodesResultData.StopMotorFVTResult.ResultCodes">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.StopMotorFVTResult.ResultCodes.MCI_CMD_ACCEPTED">
            <summary>
            The mci command accepted
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.StopMotorFVTResult.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StopMotorFVTResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StopMotorFVTResult.Code">
            <summary>
            Gets or sets the Code.
            </summary>
            <value>
            The Code.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StopMotorFVTResult.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StopMotorFVTResult.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.GetMotorFVTResult">
            <summary>
            Parse the Get Motor FVT results.
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.MotorIndex">
            <summary>
            Gets or sets the index of the motor index.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.OC">
            <summary>
            Gets or sets the OC.
            bit 0 - OC happened when it was not supposed, e.g. “check sensors” or “surge relay check” tests
            </summary>
            <value>
            The OC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.TimedOut">
            <summary>
            Gets or sets the Timed Out.
            bit 1 - Timed out when checking OC hardware. 
            </summary>
            <value>
            The timed out.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.ExpiredData">
            <summary>
            Gets or sets the ExpiredData.
            bit 2 - Data is old, e.g. the data result was read twice, may run again FVT or just ignore it.
            </summary>
            <value>
            The ExpiredData.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.InvalidDataRead">
            <summary>
            Gets or sets the InvalidRead.
            bit 3 - Attempted to read data without running FVT
            </summary>
            <value>
            The InvalidRead.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.DCBus">
            <summary>
            Gets or sets the DC Bus.
            </summary>
            <value>
            The DC Bus.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseVoltageA">
            <summary>
            Gets or sets the PhaseVoltageA.
            </summary>
            <value>
            The PhaseVoltageA.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseVoltageB">
            <summary>
            Gets or sets the PhaseVoltageB.
            </summary>
            <value>
            The PhaseVoltageB.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseVoltageC">
            <summary>
            Gets or sets the PhaseVoltageC.
            </summary>
            <value>
            The PhaseVoltageC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseCurrentA">
            <summary>
            Gets or sets the PhaseCurrentA.
            </summary>
            <value>
            The PhaseCurrentA.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseCurrentB">
            <summary>
            Gets or sets the PhaseCurrentB.
            </summary>
            <value>
            The PhaseCurrentB.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.PhaseCurrentC">
            <summary>
            Gets or sets the PhaseCurrentC.
            </summary>
            <value>
            The PhaseCurrentC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.DCBusVoltageOpen">
            <summary>
            Gets or sets the DCBusVoltageOpen.
            </summary>
            <value>
            The DCBusVoltageOpen.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.DCBusVoltageClosed">
            <summary>
            Gets or sets the DCBusVoltageClosed.
            </summary>
            <value>
            The DCBusVoltageClosed.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMotorFVTResult.CircuitOC">
            <summary>
            Gets or sets the CircuitOC.
            </summary>
            <value>
            The CircuitOC.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetMotorFVTResult.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.StartAndGetMotorFVTResult">
            <summary>
            Parse the Start and Get Motor FVT results.
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.MotorIndex">
            <summary>
            Gets or sets the index of the motor index.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.OC">
            <summary>
            Gets or sets the OC.
            bit 0 - OC happened when it was not supposed, e.g. “check sensors” or “surge relay check” tests
            </summary>
            <value>
            The OC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.TimedOut">
            <summary>
            Gets or sets the Timed Out.
            bit 1 - Timed out when checking OC hardware. 
            </summary>
            <value>
            The timed out.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.ExpiredData">
            <summary>
            Gets or sets the ExpiredData.
            bit 2 - Data is old, e.g. the data result was read twice, may run again FVT or just ignore it.
            </summary>
            <value>
            The ExpiredData.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.StartMotorFVTError">
            <summary>
            Gets or sets the error.
            </summary>
            <value>
            The error.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.InvalidDataRead">
            <summary>
            Gets or sets the InvalidRead.
            bit 3 - Attempted to read data without running FVT
            </summary>
            <value>
            The InvalidRead.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.DCBus">
            <summary>
            Gets or sets the DC Bus.
            </summary>
            <value>
            The DC Bus.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseVoltageA">
            <summary>
            Gets or sets the PhaseVoltageA.
            </summary>
            <value>
            The PhaseVoltageA.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseVoltageB">
            <summary>
            Gets or sets the PhaseVoltageB.
            </summary>
            <value>
            The PhaseVoltageB.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseVoltageC">
            <summary>
            Gets or sets the PhaseVoltageC.
            </summary>
            <value>
            The PhaseVoltageC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseCurrentA">
            <summary>
            Gets or sets the PhaseCurrentA.
            </summary>
            <value>
            The PhaseCurrentA.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseCurrentB">
            <summary>
            Gets or sets the PhaseCurrentB.
            </summary>
            <value>
            The PhaseCurrentB.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.PhaseCurrentC">
            <summary>
            Gets or sets the PhaseCurrentC.
            </summary>
            <value>
            The PhaseCurrentC.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.DCBusVoltageOpen">
            <summary>
            Gets or sets the DCBusVoltageOpen. Average DC bus voltage while injection DC bus voltage with surge relay open. 
            </summary>
            <value>
            The DCBusVoltageOpen.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.DCBusVoltageClosed">
            <summary>
            Gets or sets the DCBusVoltageClosed. Average DC bus voltage while injection DC bus voltage with surge relay closed. 
            </summary>
            <value>
            The DCBusVoltageClosed.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StartAndGetMotorFVTResult.CircuitOC">
            <summary>
            Gets or sets the CircuitOC.
            TRUE - An over current was triggerd by applying high voltage therefore high currents
            FALSE - No over current was triggered by applying high voltage
            </summary>
            <value>
            The CircuitOC.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StartAndGetMotorFVTResult.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.OpcodesResultData.GetMCIErrorResult">
            <summary>
            Parse the door sensor check
            Class B software, requires the door to be closed in order for class A software to control.
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.MCIErrorFound">
            <summary>
            Gets or sets a value indicating whether any error was found from MCI.
            </summary>
            <value>
              <c>true</c> if [error found]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.InitializationFailed">
            <summary>
            Gets or sets a value indicating whether [initialization failed].
            </summary>
            <value>
              <c>true</c> if [initialization failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.DCBusOverVoltage">
            <summary>
            Gets or sets a value indicating whether [dc bus over voltage].
            </summary>
            <value>
              <c>true</c> if [dc bus over voltage]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.DCBusUnderVoltage">
            <summary>
            Gets or sets a value indicating whether [database bus under voltage].
            </summary>
            <value>
              <c>true</c> if [database bus under voltage]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.InverterOverTemp">
            <summary>
            Gets or sets a value indicating whether [inverter over temporary].
            </summary>
            <value>
              <c>true</c> if [inverter over temporary]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.LockedRotorAtStartup">
            <summary>
            Gets or sets a value indicating whether [locked rotor at start up].
            </summary>
            <value>
              <c>true</c> if [locked rotor at start up]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.LockedRotorInRunning">
            <summary>
            Gets or sets a value indicating whether [locked rotor in running].
            </summary>
            <value>
              <c>true</c> if [locked rotor in running]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.MotorOverheating">
            <summary>
            Gets or sets a value indicating whether [motor overheating].
            </summary>
            <value>
              <c>true</c> if [motor overheating]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.CurrentSensorFailed">
            <summary>
            From Class B - Gets or sets a value indicating whether [current sensor failed].
            </summary>
            <value>
              <c>true</c> if [current sensor failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.VoltageSensorFailed">
            <summary>
            From Class B - Gets or sets a value indicating whether [voltage sensor failed].
            </summary>
            <value>
              <c>true</c> if [voltage sensor failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.SWOverCurrent">
            <summary>
            Gets or sets a value indicating whether [software/logic over current].
            </summary>
            <value>
              <c>true</c> if [software/logic over current]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.HWOverCurrent">
            <summary>
            Gets or sets a value indicating whether [peripheral/hardware over current].
            </summary>
            <value>
              <c>true</c> if [peripheral/hardware over current]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.SpeedCheckFailed">
            <summary>
            Gets or sets a value indicating whether [speed check failed].
            </summary>
            <value>
              <c>true</c> if [speed check failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.PhaseLost">
            <summary>
            Gets or sets a value indicating whether [phase lost].
            </summary>
            <value>
              <c>true</c> if [phase lost]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.InputCapturePlausibilityMinFailed">
            <summary>
            Gets or sets a value indicating whether [input capture plausibility minimum failed].
            </summary>
            <value>
              <c>true</c> if [input capture plausibility minimum failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.InputCapturePlausibilityMaxFailed">
            <summary>
            Gets or sets a value indicating whether [input capture plausibility maximum failed].
            </summary>
            <value>
              <c>true</c> if [input capture plausibility maximum failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.InterruptDisabled">
            <summary>
            Gets or sets a value indicating whether [interrupt disabled].
            </summary>
            <value>
              <c>true</c> if [interrupt disabled]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.StratorOverTemp">
            <summary>
            Gets or sets a value indicating whether [strator over temporary].
            </summary>
            <value>
              <c>true</c> if [strator over temporary]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.ClassBForcedToStop">
            <summary>
            Gets or sets a value indicating whether [Class B forced to stop].
            </summary>
            <value>
              <c>true</c> if [Class B forced to stop]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.ShutdownHardwareFailed">
            <summary>
            Gets or sets a value indicating whether [shutdown hardware failed].
            </summary>
            <value>
              <c>true</c> if [shutdown hardware failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.ObserverFailure">
            <summary>
            Gets or sets a value indicating whether [observer failure].
            </summary>
            <value>
              <c>true</c> if [observer failure]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.GetMCIErrorResult.DCBusOutOfRange">
            <summary>
            Gets or sets a value indicating whether [dc bus out of range].
            </summary>
            <value>
              <c>true</c> if [dc bus out of range]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.GetMCIErrorResult.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            
        </member>
        <member name="T:NTL.OpcodesResultData.FailureFlags">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.FailureFlagsBitmap">
            <summary>
            Gets or sets the flags.
            </summary>
            <value>
            The flags.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.Flags">
            <summary>
            Gets or sets the flags.
            </summary>
            <value>
            The flags.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.AnyErrorFound">
            <summary>
            Gets or sets a value indicating whether [any error found].
            </summary>
            <value>
              <c>true</c> if [any error found]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.DCbusOverCurrent">
            <summary>
            Gets or sets a value indicating whether [d cbus over current].
            </summary>
            <value>
              <c>true</c> if [d cbus over current]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.DCbusOverVoltage">
            <summary>
            Gets or sets a value indicating whether [d cbus over voltage].
            </summary>
            <value>
              <c>true</c> if [d cbus over voltage]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.DCbusUnderVoltage">
            <summary>
            Gets or sets a value indicating whether [d cbus under voltage].
            </summary>
            <value>
              <c>true</c> if [d cbus under voltage]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.ElectronicFailed">
            <summary>
            Gets or sets a value indicating whether [electronic failed].
            </summary>
            <value>
              <c>true</c> if [electronic failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.reserved1">
            <summary>
            The reserved1
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.Reserved1">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.OpcodesResultData.FailureFlags" /> is reserved1.
            </summary>
            <value>
              <c>true</c> if reserved1; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.reserved2">
            <summary>
            The reserved2
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.Reserved2">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.OpcodesResultData.FailureFlags" /> is reserved2.
            </summary>
            <value>
              <c>true</c> if reserved2; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.inverterOverTemp">
            <summary>
            The inverter over temporary
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.InverterOverTemp">
            <summary>
            Gets or sets a value indicating whether [inverter over temporary].
            </summary>
            <value>
            <c>true</c> if [inverter over temporary]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.reserved3">
            <summary>
            The reserved3
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.Reserved3">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.OpcodesResultData.FailureFlags"/> is reserved3.
            </summary>
            <value>
              <c>true</c> if reserved3; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.statorOverTemp">
            <summary>
            The stator over temporary
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.StatorOverTemp">
            <summary>
            Gets or sets a value indicating whether [stator over temporary].
            </summary>
            <value>
              <c>true</c> if [stator over temporary]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.lockedRotor">
            <summary>
            The locked rotor
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.LockedRotor">
            <summary>
            Gets or sets a value indicating whether [locked rotor].
            </summary>
            <value>
              <c>true</c> if [locked rotor]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.phaseLost">
            <summary>
            The phase lost
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.PhaseLost">
            <summary>
            Gets or sets a value indicating whether [phase lost].
            </summary>
            <value>
              <c>true</c> if [phase lost]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.reserved4">
            <summary>
            The reserved4
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.Reserved4">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.OpcodesResultData.FailureFlags"/> is reserved4.
            </summary>
            <value>
              <c>true</c> if reserved4; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.motorOverheating">
            <summary>
            The motor overheating
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MotorOverheating">
            <summary>
            Gets or sets a value indicating whether [motor overheating].
            </summary>
            <value>
              <c>true</c> if [motor overheating]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.motorOverloaded">
            <summary>
            The motor overloaded
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MotorOverloaded">
            <summary>
            Gets or sets a value indicating whether [motor overloaded].
            </summary>
            <value>
              <c>true</c> if [motor overloaded]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.motorOverCurrent">
            <summary>
            The motor over current
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MotorOverCurrent">
            <summary>
            Gets or sets a value indicating whether [motor over current].
            </summary>
            <value>
              <c>true</c> if [motor over current]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.motorUnderCurrent">
            <summary>
            The motor under current
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.MotorUnderCurrent">
            <summary>
            Gets or sets a value indicating whether [motor under current].
            </summary>
            <value>
              <c>true</c> if [motor under current]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.OpcodesResultData.FailureFlags.speedCheckFailed">
            <summary>
            The speed check failed
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.FailureFlags.SpeedCheckFailed">
            <summary>
            Gets or sets a value indicating whether [speed check failed].
            </summary>
            <value>
              <c>true</c> if [speed check failed]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.FailureFlags.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.MotorStatus">
            <summary>
            Parses the motor status
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.MotorStatus.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.Status">
            <summary>
            Gets or sets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.AnyErrorFound">
            <summary>
            Gets or sets a value indicating whether [any error found].
            </summary>
            <value>
              <c>true</c> if [any error found]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.IsMotorStopped">
            <summary>
            Gets or sets a value indicating whether this instance is motor stopped.
            </summary>
            <value>
            <c>true</c> if this instance is motor stopped; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.Reachedtarget">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.OpcodesResultData.MotorStatus"/> is reachedtarget.
            </summary>
            <value>
              <c>true</c> if reachedtarget; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.IsIdle">
            <summary>
            Gets or sets a value indicating whether this instance is idle.
            </summary>
            <value>
              <c>true</c> if this instance is idle; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.MotorRunning">
            <summary>
            Gets or sets a value indicating whether [motor running].
            </summary>
            <value>
              <c>true</c> if [motor running]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.MotorStatus.StatusFlagsBitmap">
            <summary>
            Gets the status flags bitmap.
            </summary>
            <value>
            The status flags bitmap.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.MotorStatus.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.AnalogData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.AnalogData.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.MotorIndex">
            <summary>
            Gets or sets the index of the motor.
            </summary>
            <value>
            The index of the motor.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.AnalogChannel">
            <summary>
            Gets or sets the analog channel.
            </summary>
            <value>
            The analog channel.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.AnalogDataValueBytes">
            <summary>
            Gets the analog data value bytes.
            </summary>
            <value>
            The analog data value bytes.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.AnalogData.AnalogDataValue">
            <summary>
            The analog data value
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.AnalogData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.StreamAnalogDdata">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.StreamAnalogDdata.streamAnalogData">
            <summary>
            The stream analog data
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.StreamAnalogDdata.StreamAnalogData">
            <summary>
            Gets or sets the stream analog data.
            </summary>
            <value>
            The stream analog data.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StreamAnalogDdata.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.StreamAnalogDdata.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.StreamAnalogDdata.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.PeriodicDataStaus">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.PeriodicDataStaus.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.PeriodicDataStaus.analogChannelsBitmap">
            <summary>
            The analog channels bitmap
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.PeriodicDataStaus.AnalogChannelsBits">
            <summary>
            The analog channels bits
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.PeriodicDataStaus.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PeriodicDataStaus.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PeriodicDataStaus.msPeriod">
            <summary>
            Gets the ms period.
            </summary>
            <value>
            The ms period.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.PeriodicDataStaus.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.PublishEvent">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="F:NTL.OpcodesResultData.PublishEvent.requestResult">
            <summary>
            The request result
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishEvent.MotorIndex">
            <summary>
            The motor index
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishEvent.OccuredEvent">
            <summary>
            The occured event
            </summary>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishEvent.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.PublishEvent.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.PublishEvent.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.OpcodesResultData.Status">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Status.ANY_ERROR_FOUND">
            <summary>
            Any error found
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Status.IS_MOTOR_STOPPED">
            <summary>
            The motor has stopped
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Status.REACHED_TARGET">
            <summary>
            The target velocity equals the reference velocity
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Status.IS_IDLE">
            <summary>
            The motor has stopped and no error is found
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Status.MOTOR_RUNNING">
            <summary>
            The motor is running
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.Flags">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.ANY_ERROR_FOUND">
            <summary>
            Any error found
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.DCBUS_OVER_CURRENT">
            <summary>
            DC bus link over current detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.DCBUS_OVER_VOLTAGE">
            <summary>
            The dcbus over voltage detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.DCBUS_UNDER_VOLTAGE">
            <summary>
            The dcbus under voltage detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.ELECTRONIC_FAILED">
            <summary>
            The electronic drive failed
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.Reserved1">
            <summary>
            The reserved1
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.Reserved2">
            <summary>
            The reserved2
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.INVERTER_OVER_TEMP">
            <summary>
            Module over temperature
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.Reserved3">
            <summary>
            The reserved3
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.STATOR_OVER_TEMP">
            <summary>
            The stator temperature exceeded the limit and will prevent
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.LOCKED_ROTOR">
            <summary>
            Rotor is locked according to ClassB feedback
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.PHASE_LOST">
            <summary>
            The phase lost detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.Reserved4">
            <summary>
            The reserved4
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.MOTOR_OVERHEATING">
            <summary>
            The motor overheating
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.MOTOR_OVERLOADED">
            <summary>
            The motor overloaded
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.MOTOR_OVER_CURRENT">
            <summary>
            The motor over current detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.MOTOR_UNDER_CURRENT">
            <summary>
            The motor under current detected
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Flags.SPEED_CHECK_FAILED">
            <summary>
            Safety speed check for door unlock failed
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.Event">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Event.API221_EVENT_ERROR">
            <summary>
            Event occurs when the MCU encounters an error.
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Event.API221_EVENT_STOPPED">
            <summary>
            The ap i221 event stopped
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Event.API221_EVENT_RAMP_STARTED">
            <summary>
            The ap i221 event ramp started
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Event.API221_EVENT_TARGET_REACHED">
            <summary>
            The ap i221 event target reached
            </summary>
        </member>
        <member name="F:NTL.OpcodesResultData.Event.PLATFORM_SPECIFIC_EVENTS">
            <summary>
            The platform specific events
            </summary>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileProgress">
            <summary>
            Provides the status, completion and ellapsed time of Setting file download process
            </summary>
            <seealso cref="T:NTL.OpcodesResultData.ISettingFileProgress" />
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgress.Completion">
            <summary>
            Gets the completion percentage.
            </summary>
            <value>
            The completion percentage.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgress.Status">
            <summary>
            Gets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgress.EllapsedTime">
            <summary>
            Gets the ellapsed time.
            </summary>
            <value>
            The ellapsed time.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgress.State">
            <summary>
            Gets the state.
            </summary>
            <value>
            The state.
            </value>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileProgress.Report(NTL.OpcodesResultData.SettingFileProgressArgs)">
            <summary>
            Reports the setting file download progress.
            </summary>
            <param name="value">The value.</param>
        </member>
        <member name="T:NTL.OpcodesResultData.SettingFileProgressArgs">
            <summary>
            
            Setting file progress Args definition
            </summary>
        </member>
        <member name="M:NTL.OpcodesResultData.SettingFileProgressArgs.#ctor(System.Int32,System.String,System.Int64,NTL.SFDownloadState)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.OpcodesResultData.SettingFileProgressArgs" /> class.
            </summary>
            <param name="completion">The completion.</param>
            <param name="status">The status.</param>
            <param name="ellapsedTime">The ellapsed time.</param>
            <param name="state">The state.</param>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgressArgs.Completion">
            <summary>
            Gets the completion percentage.
            </summary>
            <value>
            The completion percentage.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgressArgs.Status">
            <summary>
            Gets the status.
            </summary>
            <value>
            The status.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgressArgs.State">
            <summary>
            Gets the state.
            </summary>
            <value>
            The state.
            </value>
        </member>
        <member name="P:NTL.OpcodesResultData.SettingFileProgressArgs.EllapsedTime">
            <summary>
            Gets the ellapsed time.
            </summary>
            <value>
            The ellapsed time.
            </value>
        </member>
        <member name="T:NTL.OpcodesResultData.ISettingFileProgress">
            <summary>
            Interface to implement the report progress.
            </summary>
            <seealso cref="T:System.IProgress`1" />
        </member>
        <member name="T:NTL.IAP.IAPHandler">
            <summary>
            
            1. Load s19: it is the most time-consuming part, then must be executed before everything
            2. Start Record
            3. API 9, OP CODE 1 -> From this point the procedure must start in max 2 seconds
            4. wait for ...
            5. Start Programming
            </summary>
            <seealso cref="T:System.IDisposable" />
        </member>
        <member name="M:NTL.IAP.IAPHandler.#ctor(WhirlpoolCommunication.IDevice)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.IAP.IAPHandler"/> class.
            </summary>
            <param name="device">The device.</param>
        </member>
        <member name="M:NTL.IAP.IAPHandler.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="data">The data.</param>
        </member>
        <member name="M:NTL.IAP.IAPHandler.NodeInfoRequest(System.Byte,System.Int32)">
            <summary>
            Nodes the information request.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.BuildIAPPacket(ProgramAgentLib.IAPPacket.CMD_ID,System.Byte,System.Byte[])">
            <summary>
            Builds the iap packet.
            </summary>
            <param name="cmd">The command.</param>
            <param name="node">The node.</param>
            <param name="data">The data.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.SetData(System.Collections.Generic.List{NTL.IAP.IAPResultData.IIAPData},ProgramAgentLib.IAPPacket,NTL.IAP.WaitableIAPMessageQueue,System.Int32,System.Collections.Generic.List{ProgramAgentLib.IAPPacket})">
            <summary>
            Sets the data.
            </summary>
            <param name="results">The results.</param>
            <param name="requestMessage">The request message.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <param name="prependMessages">The prepend messages.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.WaitForMessageQueue(System.Collections.Generic.List{NTL.IAP.IAPResultData.IIAPData},NTL.IAP.WaitableIAPMessageQueue,System.Int32)">
            <summary>
            Waits for message queue.
            </summary>
            <param name="results">The results.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.SetFlashProgramming(System.Byte)">
            <summary>
            Sets the flash programming.
            </summary>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.EnterIAP(System.Byte)">
            <summary>
            Enters the iap.
            </summary>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.ExitIAP(System.Byte)">
            <summary>
            Exits the iap.
            </summary>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.StopProgramming(System.Byte)">
            <summary>
            Stops the programming.
            </summary>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.FlashFirmware(System.Threading.CancellationTokenSource,ProgramAgentLib.IPAEngineProgress,System.IO.Stream,System.Byte,System.UInt16,System.Boolean)">
            <summary>
            Flashes the firmware.
            </summary>
            <param name="cancelDownload"></param>
            <param name="progress">The progress.</param>
            <param name="stream">The stream.</param>
            <param name="target">The target.</param>
            <param name="timerReset">The timer reset.</param>
            <param name="fullChipErase">if set to <c>true</c> [full chip erase].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.IAP.IAPHandler.SetLogger(WhirlpoolCommunication.Utilities.Logger.ILogger)">
            <summary>
            Sets the logger.
            </summary>
            <param name="logger">The logger.</param>
        </member>
        <member name="T:NTL.IAP.IAPResultData.IAPNodeInfo">
            <summary>
            Provides the status, completion and ellapsed time of Setting file download process
            </summary>
            <seealso cref="T:ProgramAgentLib.IPAEngineProgress" />
        </member>
        <member name="M:NTL.IAP.IAPResultData.IAPNodeInfo.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.IAP.IAPResultData.IAPNodeInfo"/> class.
            </summary>
            <param name="messageId">The message identifier.</param>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.Cmd_Status_Fbd">
            <summary>
            Gets the command status FBD.
            </summary>
            <value>
            The command status FBD.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.Engine_Status_Fbd">
            <summary></summary>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.Max_Speed_Fbd">
            <summary>
            Gets the maximum speed FBD.
            </summary>
            <value>
            The maximum speed FBD.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.Max_Payload_Fbd">
            <summary>
            Gets the maximum payload FBD.
            </summary>
            <value>
            The maximum payload FBD.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.SotwareVersion">
            <summary>
            Gets the sotware version.
            </summary>
            <value>
            The sotware version.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.ReleaseDate">
            <summary>
            Gets the release date.
            </summary>
            <value>
            The release date.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.Timeout">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
            <exception cref="T:System.NotImplementedException">
            </exception>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IAPNodeInfo.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="M:NTL.IAP.IAPResultData.IAPNodeInfo.ParseData(System.Collections.Generic.IEnumerable{ProgramAgentLib.IAPPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.IAP.IAPResultData.IIAPData">
            <summary>
            
            </summary>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IIAPData.Timeout">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.IAP.IAPResultData.IIAPData"/> is timeout.
            </summary>
            <value>
              <c>true</c> if timeout; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.IAP.IAPResultData.IIAPData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="M:NTL.IAP.IAPResultData.IIAPData.ParseData(System.Collections.Generic.IEnumerable{ProgramAgentLib.IAPPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.IAP.NodeInfoRequestWaitableMessage">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.IAP.NodeInfoRequestWaitableMessage.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.IAP.NodeInfoRequestWaitableMessage"/> class.
            </summary>
        </member>
        <member name="M:NTL.IAP.NodeInfoRequestWaitableMessage.GetIAPNodeInfoWaitableMessage(System.String,System.Byte)">
            <summary>
            Gets the iap node information waitable message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="count">The count.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.IAP.WaitableIAPMessage">
            <summary>
            
            </summary>
            <seealso cref="!:NTL.WaitableMessage&lt;ProgramAgentLib.IAPPacket&gt;" />
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.Source">
            <summary>
            Gets or sets the source.
            </summary>
            <value>
            The source.
            </value>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.Destination">
            <summary>
            Gets or sets the destination.
            </summary>
            <value>
            The destination.
            </value>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.CmdID">
            <summary>
            Gets or sets the command identifier.
            </summary>
            <value>
            The command identifier.
            </value>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.Count">
            <summary>
            Gets or sets the count.
            </summary>
            <value>
            The count.
            </value>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.Fbd_Status">
            <summary>
            Gets or sets the FBD status.
            </summary>
            <value>
            The FBD status.
            </value>
        </member>
        <member name="F:NTL.IAP.WaitableIAPMessage.payload">
            <summary>
            The payload
            </summary>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.Payload">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="F:NTL.IAP.WaitableIAPMessage.payloadmask">
            <summary>
            The payloadmask
            </summary>
        </member>
        <member name="P:NTL.IAP.WaitableIAPMessage.PayloadMask">
            <summary>
            Gets or sets the data mask.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.IAP.WaitableIAPMessage.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.IAP.WaitableIAPMessage"/> class.
            </summary>
            <param name="id">The identifier.</param>
        </member>
        <member name="M:NTL.IAP.WaitableIAPMessage.CompareTo(ProgramAgentLib.IAPPacket,System.Boolean)">
            <summary>
            Compares to the message incoming to the waitable message
            </summary>
            <param name="data">The data.</param>
            <param name="setMessageMatch">if set to <c>true</c> set message match if compare is true.</param>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="M:NTL.IAP.WaitableIAPMessage.FixBinaryMask">
            <summary>
            Fixes the binary mask.
            </summary>
        </member>
        <member name="T:NTL.IAP.WaitableIAPMessageQueue">
            <summary>
            
            </summary>
            <seealso cref="!:NTL.WaitableMessageQueue&lt;NTL.Firmware.WaitableIAPMessage&gt;" />
        </member>
        <member name="M:NTL.IAP.WaitableIAPMessageQueue.CompareTo(ProgramAgentLib.IAPPacket)">
            <summary>
            Compares the incoming message against the queue.
            Returns true if the message matches and set the MessageMatch.
            </summary>
            <param name="incomingMessage">The incoming message.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.NKMParser.NKMHandler">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.UNSIGNED_8">
            <summary>
            The unsigned8 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.UNSIGNED_16">
            <summary>
            The unsigned16 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.UNSIGNED_32">
            <summary>
            The unsigned32 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.UNSIGNED_64">
            <summary>
            The unsigned64 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.SIGNED_8">
            <summary>
            The signed8 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.SIGNED_16">
            <summary>
            The signed16 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.SIGNED_32">
            <summary>
            The signed32 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.SIGNED_64">
            <summary>
            The signed64 
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.FLOAT_32">
            <summary>
            The bit32 floatingpoint
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.FLOAT_64">
            <summary>
            The bit64 floatingpoint
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.Q15_CELSIUS">
            <summary>
            The Q15 celsius
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.Q15_FORMAT">
            <summary>
            The Q15 format
            </summary>
        </member>
        <member name="F:NTL.NKMParser.NKMHandler.NucleusVariableDataTypes.DATATYPE_TTE_VISUALIZER">
            <summary>
            The TTE_Visualizer format
            </summary>
        </member>
        <member name="P:NTL.NKMParser.NKMHandler.Configurations">
            <summary>
            Gets or sets the configurations.
            </summary>
            <value>
            The configurations.
            </value>
        </member>
        <member name="M:NTL.NKMParser.NKMHandler.LabelFileParser(System.IO.Stream)">
            <summary>
            Parses the label file .
            </summary>
            <param name="XMLStream">The XML stream.</param>
        </member>
        <member name="M:NTL.NKMParser.NKMHandler.GetVariableInformation(System.Int32)">
            <summary>
            Gets the variable information.
            Note: Need to use NKM xml file and invoke the LabelFileParser function of NKMHandler class before using this function.
            </summary>
            <param name="productTypeID">Type of the product.</param>
            <returns><see cref="T:NTL.OpcodesResultData.VariableInfo"/></returns>
        </member>
        <member name="M:NTL.NKMParser.NKMHandler.GetVarInfoById(System.UInt32,System.Int32)">
            <summary>
            Gets the variable information by variable Id.
            Note: Need to use NKM xml file and invoke the LabelFileParser function of NKMHandler class before using this function.
            <example> The following example shows how GetVariableInfobyId is used in to Stream variables data function of NTL in C#
            <code lang="C#" title="C#" region="API10 variable stream example" /></example>.
            </summary>
            <param name="id">The identifier.</param>
            <param name="productType">Type of the product.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.VariableInfo" />
            </returns>
        </member>
        <member name="M:NTL.NKMParser.NKMHandler.GetVarInfoByName(System.String,System.Int32)">
            <summary>
            Gets variable information by variable name.
            Note: Need to use NKM xml file and invoke the LabelFileParser function of NKMHandler class before using this function.
            <example> The following example shows how GetVariableInfobyId is used in to Stream variables data function of NTL in C#
            <code lang="C#" title="C#" region="API10 variable stream example" /></example>.
            </summary>
            <param name="varName">Name of the variable.</param>
            <param name="productType">Type of the product.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.VariableInfo" />
            </returns>
        </member>
        <member name="T:NTL.NKMParser.Configurations">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.ProductTypes">
            <summary>
            The product types
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.LowLevelInputs">
            <summary>
            The low level inputs
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.Loads">
            <summary>
            The loads
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.Regulations">
            <summary>
            The regulations
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.PilotTypes">
            <summary>
            The pilot types
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.GenericInputs">
            <summary>
            The generic inputs
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.Cycles">
            <summary>
            The cycles
            </summary>
        </member>
        <member name="F:NTL.NKMParser.Configurations.Faults">
            <summary>
            The faults
            </summary>
        </member>
        <member name="T:NTL.NKMParser.Fault">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.NKMParser.Cycle">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.NKMParser.GenericInput">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.NKMParser.LowlevelInputs" />
        </member>
        <member name="F:NTL.NKMParser.GenericInput.LowLevelInputs">
            <summary>
            The lowlevel inputs
            </summary>
        </member>
        <member name="T:NTL.NKMParser.PilotType">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.NKMParser.Regulation">
            <summary>
            
            </summary>
        </member>
        <member name="T:NTL.NKMParser.Load">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.NKMParser.NKMItem" />
        </member>
        <member name="P:NTL.NKMParser.Load.LoadType">
            <summary>
            Gets or sets the type of the load.
            </summary>
            <value>
            The type of the load.
            </value>
        </member>
        <member name="P:NTL.NKMParser.Load.PilotType">
            <summary>
            The pilot type
            </summary>
        </member>
        <member name="T:NTL.NKMParser.LowlevelInputs">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.NKMParser.NKMItem" />
        </member>
        <member name="T:NTL.NKMParser.ProductType">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.NKMParser.NKMItem" />
        </member>
        <member name="P:NTL.NKMParser.ProductType.Variables">
            <summary>
            The variables
            </summary>
        </member>
        <member name="T:NTL.NKMParser.Variable">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.NKMParser.NKMItem" />
        </member>
        <member name="P:NTL.NKMParser.Variable.DataType">
            <summary>
            Gets or sets the type of the data.
            </summary>
            <value>
            The type of the data.
            </value>
        </member>
        <member name="P:NTL.NKMParser.Variable.Offset">
            <summary>
            Gets or sets the offset.
            </summary>
            <value>
            The offset.
            </value>
        </member>
        <member name="T:NTL.NKMParser.NKMItem">
            <summary>
            Base nkm item
            </summary>
        </member>
        <member name="P:NTL.NKMParser.NKMItem.ReferenceId">
            <summary>
            Gets or sets the reference identifier.
            </summary>
            <value>
            The reference identifier.
            </value>
        </member>
        <member name="P:NTL.NKMParser.NKMItem.Name">
            <summary>
            Gets or sets the name.
            </summary>
            <value>
            The name.
            </value>
        </member>
        <member name="T:NTL.NKMParser.NamespaceDoc">
             <summary>
            Provides information about Id, Name, Offset for loads, LLIs, GIs, Pilots, Regulations, Cycles and faults 
             </summary>
        </member>
        <member name="T:NTL.NamespaceDoc">
            <summary>
            Nucleus Tools Library (NTL) provides a set of methods/functions for platforms using Nucleus architecture. It interfaces WIDEBoxLib to talk with Whirlpool bus protocols(WIDE and WIN). 
            It exposes cross platform Reveal APIs and abstracts some cross platform high level tasks from APIs, e.g. settings file download. 
            It is compiled as Portable class library
            </summary>
        </member>
        <member name="T:NTL.Reveal.NamespaceDoc">
             <summary>
            Provides methods/functions to build reveal waitable messages .
             </summary>
        </member>
        <member name="T:NTL.Reveal.AddToQueueResultData">
            <summary>
            Result of adding to Waitable Reveal Queue
            </summary>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.ID">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.Source">
            <summary>
            Gets or sets the source.
            </summary>
            <value>
            The source.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeSource">
            <summary>
            Should the serialize source.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.Destination">
            <summary>
            Gets or sets the destination.
            </summary>
            <value>
            The destination.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeDestination">
            <summary>
            Should the serialize destination.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.API">
            <summary>
            Gets or sets the API.
            </summary>
            <value>
            The API.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeAPI">
            <summary>
            Should the serialize API.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.Opcode">
            <summary>
            Gets or sets the full opcode.
            </summary>
            <value>
            The full opcode.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeOpcode">
            <summary>
            Should the serialize opcode.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.MoreMessagePending">
            <summary>
            Gets or sets the more message pending.
            </summary>
            <value>
            The more message pending.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeMoreMessagePending">
            <summary>
            Should the serialize moremessagepending.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.IsFragmented">
            <summary>
            Gets or sets the is fragmented.
            </summary>
            <value>
            The is fragmented.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeIsFragmented">
            <summary>
            Should the serialize isfragmented.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.IsFeedback">
            <summary>
            Gets or sets the is feedback.
            </summary>
            <value>
            The is feedback.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ShouldSerializeIsFeedback">
            <summary>
            Should the serialize isfeedback.
            </summary>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.Payload">
            <summary>
            Gets or sets the payload.
            </summary>
            <value>
            The payload.
            </value>
        </member>
        <member name="P:NTL.Reveal.AddToQueueResultData.PayloadMask">
            <summary>
            Gets or sets the payload mask.
            </summary>
            <value>
            The payload mask.
            </value>
        </member>
        <member name="M:NTL.Reveal.AddToQueueResultData.ParseWaitableMessage(NTL.Reveal.WaitableRevealMessage)">
            <summary>
            Parses the waitable message.
            </summary>
            <param name="waitableMessage">The waitable message.</param>
        </member>
        <member name="T:NTL.Reveal.RequestDataResult">
            <summary>
            Request data result enumerations
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.READY">
            <summary>
            The command was successfully executed and reveal is ready to accept another command.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.BUSY">
            <summary>
            The reveal module is currently busy executing a command. Usually just an internal state.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.REJECTED">
            <summary>
            The command sent to Reveal was rejected, because there was another command still in process.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.ACKEVENT">
            <summary>
            The command was not executed because Reveal is currently waiting for an acknowledgement.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUPPORTED">
            <summary>
            The command was unsupported for some reason and did not execute. (Ready for next command)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_OP_CODE">
            <summary>
            The command was unsupported and did not execute due to an invalid op code. (Ready for next command)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_UNAVAILABLE">
            <summary>
            The command was unsupported and did not execute because it is currently unavailable in this state.(Ready)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_INVALID_PARAM">
            <summary>
            The command was unsupported and did not execute due to an invalid or out of bounds parameter.(Ready)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_OUT_OF_MEMORY">
            <summary>
            The command was unsupported and did not execute because the dynamic heap is out of memory.(Ready)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_DOOR_OPEN">
            <summary>
            The command was unsupported and did not execute because the appliance door was open. (Ready)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_BOUND_CMD_INCOMPLETE">
            <summary>
            The bounded command was not fully received before a specified timeout, so it was not fully executed. (Ready)
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNSUP_CANNOT_PAUSE_NOW">
            <summary>
            Unable to pause due to state of appliance process.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.APPLICATION_SPECIFIC">
            <summary>
            Application Developers may use these return values in their applications. It is up to the Developer to document the Application Specific reason codes.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.TIMEOUT">
            <summary>
            The timeout
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.UNABLE_TO_PARSE">
            <summary>
            Unable to parse the incoming data from the target.
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.APPLICATION_ERROR">
            <summary>
            The application error
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.INVALID">
            <summary>
            The invalid
            </summary>
        </member>
        <member name="F:NTL.Reveal.RequestDataResult.CANCELLED">
            <summary>
            The cancelled
            </summary>
        </member>
        <member name="T:NTL.Reveal.IRevealData">
            <summary>
            Reveal data interface
            </summary>
        </member>
        <member name="P:NTL.Reveal.IRevealData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.Reveal.IRevealData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="M:NTL.Reveal.IRevealData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingMessages">The incoming messages.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.Reveal.IVariableData">
            <summary>
            Variable data interface
            </summary>
        </member>
        <member name="P:NTL.Reveal.IVariableData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="P:NTL.Reveal.IVariableData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="M:NTL.Reveal.IVariableData.ParseData(WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Parses the data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="P:NTL.Reveal.IVariableData.VariableDataType">
            <summary>
            Gets or sets the type of the variable data.
            </summary>
            <value>
            The type of the variable data.
            </value>
        </member>
        <member name="P:NTL.Reveal.IVariableData.Offset">
            <summary>
            Gets or sets the offset.
            </summary>
            <value>
            The offset.
            </value>
        </member>
        <member name="T:NTL.Reveal.RevealData">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.Reveal.IRevealData" />
        </member>
        <member name="P:NTL.Reveal.RevealData.MessageId">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.Reveal.RevealData.RequestResult">
            <summary>
            Gets or sets the request result.
            </summary>
            <value>
            The request result.
            </value>
        </member>
        <member name="M:NTL.Reveal.RevealData.ParseData(System.Collections.Generic.IEnumerable{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Parses the payload data.
            </summary>
            <param name="incomingData">The incoming data.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.Reveal.RevealHandler">
            <summary>
            Contains methods to handle reveal requests
            </summary>
        </member>
        <member name="P:NTL.Reveal.RevealHandler.IdCount">
            <summary>
            Gets or sets the identifier count.
            </summary>
            <value>
            The identifier count.
            </value>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SetLogger(WhirlpoolCommunication.Utilities.Logger.ILogger)">
            <summary>
            Sets the logger.
            Set null to stop logging.
            </summary>
            <param name="logger">The logger.</param>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.#ctor(WhirlpoolCommunication.IDevice,System.Boolean)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.Reveal.RevealHandler" /> class.
            </summary>
            <param name="deviceLocal">The device local.</param>
            <param name="disableGetMessage">if set to <c>true</c> [disable get message].</param>
            <exception cref="T:System.ArgumentNullException">deviceLocal;Device cannot be null</exception>
        </member>
        <member name="P:NTL.Reveal.RevealHandler.RXTaskStatus">
            <summary>
            Gets the RX task status. RX task gets the device messages from the WIN bus. Use RXTaskStatus function to make 
            sure RXTask is started before usinf any other Get/Set functions from the RevealHandler. Refer <see cref="T:System.Threading.Tasks.TaskStatus"/> for
            status definitions.
            </summary>
            <value>
            The rx task status.
            </value>
        </member>
        <member name="P:NTL.Reveal.RevealHandler.EnableAutoAck">
            <summary>
            Gets or sets a value indicating whether [enable automatic ack].
            </summary>
            <value>
              <c>true</c> if [enable automatic ack]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.Reveal.RevealHandler.AutoAckAPIs">
            <summary>
            Gets or sets the automatic ack ap is.
            </summary>
            <value>
            The automatic ack ap is.
            </value>
        </member>
        <member name="P:NTL.Reveal.RevealHandler.AutoAckOpcodes">
            <summary>
            Gets or sets the automatic ack opcodes.
            </summary>
            <value>
            The automatic ack opcodes.
            </value>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SetEnableAutoAcknowledge(System.Boolean,System.Byte[],System.Byte[])">
            <summary>
            Sets the enable automatic acknowledge.
            </summary>
            <param name="enable">if set to <c>true</c> [enable].</param>
            <param name="apisToIgnore">The apis to ignore.</param>
            <param name="opcodesToIgnore">The opcodes to ignore.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the Extended simple Whirlpool message.
            </summary>
            <param name="msg">The MSG.</param>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.GetRevealPackets(System.Byte,System.Byte,System.Byte,System.Byte,System.Boolean,System.Byte[],System.Int32)">
            <summary>
            Gets the reveal packets out of the given info.
            Converts payloads into multiple packages if does not fit in the max size given.
            </summary>
            <param name="api">The API.</param>
            <param name="opcode">The opcode.</param>
            <param name="source">The source.</param>
            <param name="destination">The destination.</param>
            <param name="isFeedback">if set to <c>true</c> [is feedback].</param>
            <param name="payload">The payload.</param>
            <param name="maxPayloadSize">Maximum size of the payload.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.RequestData(WhirlpoolCommunication.Packets.RevealPacket,NTL.Reveal.WaitableRevealMessageQueue,System.Int32,System.Collections.Generic.List{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Requests the data.
            </summary>
            <param name="requestMessage">The request message.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <returns><see cref="T:NTL.Reveal.RevealData"/></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.RequestData(System.Collections.Generic.List{NTL.Reveal.IRevealData},WhirlpoolCommunication.Packets.RevealPacket,NTL.Reveal.WaitableRevealMessageQueue,System.Int32,System.Collections.Generic.List{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Requests the data.
            </summary>
            <param name="results">The results.</param>
            <param name="requestMessage">The request message.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <param name="prependMessages">The prepend messages.</param>
            <returns>
              <see cref="T:NTL.Reveal.IRevealData" />
            </returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SetData(System.Collections.Generic.List{NTL.Reveal.IRevealData},WhirlpoolCommunication.Packets.RevealPacket,NTL.Reveal.WaitableRevealMessageQueue,System.Int32,System.Collections.Generic.List{WhirlpoolCommunication.Packets.RevealPacket})">
            <summary>
            Sends the requestMessage to the device.
            </summary>
            <param name="results">The results.</param>
            <param name="requestMessage">The request message.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.Reveal.IRevealData" />
            </returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.WaitForMessageQueue(System.Collections.Generic.List{NTL.Reveal.IRevealData},NTL.Reveal.WaitableRevealMessageQueue,System.Int32)">
            <summary>
            Waits for message queue.
            </summary>
            <param name="results">The results.</param>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.WaitMessage(NTL.Reveal.WaitableRevealMessageQueue,System.Int32)">
            <summary>
            Waits for the specified waitable message queue.
            </summary>
            <param name="waitableMessageQueue">The waitable message queue.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.Reveal.RevealData" />
            </returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.WaitMessage(System.Byte,System.Byte,System.Byte[],System.Byte[],System.Int32,System.Int32,System.Int32)">
            <summary>
            Waits for the message with specified parameters.
            </summary>
            <param name="api">The API.</param>
            <param name="fullOpcode">The full opcode. Includes MMP,FRAG and CMD/FBK bits.</param>
            <param name="payload">The payload.</param>
            <param name="payloadMask">The payload mask.</param>
            <param name="source">The source.</param>
            <param name="destination">The destination.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.Reveal.RevealData" />
            </returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SendAndWaitMessage(System.Byte,System.Byte,System.Byte,System.Byte[],System.Byte,System.Byte,System.Byte[],System.Byte[],System.Int32,System.Int32,System.Int32)">
            <summary>
            Sends the and wait message.
            </summary>
            <param name="target">The target.</param>
            <param name="api">The API.</param>
            <param name="fullOpcode">The full opcode.</param>
            <param name="payload">The payload.</param>
            <param name="expectedApi">The expected API.</param>
            <param name="expectedFullOpcode">The expected full opcode.</param>
            <param name="expectedPayload">The expected payload.</param>
            <param name="expectedPayloadMask">The expected payload mask.</param>
            <param name="expectedSource">The expected source.</param>
            <param name="expectedDestination">The expected destination.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.CreateWaitableRevealMessage(System.String,System.Byte,System.Byte,System.Byte[],System.Byte[],System.Int32,System.Int32)">
            <summary>
            Creates the waitable reveal message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="api">The API.</param>
            <param name="fullOpcode">The full opcode.</param>
            <param name="payload">The payload.</param>
            <param name="payloadMask">The payload mask.</param>
            <param name="source">The source.</param>
            <param name="destination">The destination.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.Subscribe(NTL.Reveal.WaitableRevealMessageQueue)">
            <summary>
            Subscribes the specified waitable message queue.
            </summary>
            <param name="waitableMessageQueue">The waitable message queue.</param>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.AddToWaitMessageQueue(System.String,System.Byte,System.Byte,System.Byte[],System.Byte[],System.Int32,System.Int32)">
            <summary>
            Adds the message to wait queue.
            </summary>
            <param name="id">The identifier.</param>
            <param name="api">The API.</param>
            <param name="fullOpcode">The full opcode. Includes MMP,FRAG and CMD/FBK bits.</param>
            <param name="payload">The payload.</param>
            <param name="payloadMask">The payload mask.</param>
            <param name="source">The source.</param>
            <param name="destination">The destination.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.WaitMessageQueue(System.Int32)">
            <summary>
            Waits the message queue.
            </summary>
            <param name="timeout">The timeout.</param> 
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.ClearWaitMessageQueue">
            <summary>
            Clears the wait message queue.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SendMessage(WhirlpoolCommunication.Packets.RevealPacket,System.Int32)">
            <summary>
            Send Message.
            </summary>
            <param name="rvp">The RVP.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SendMessage(System.Byte,System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sends the message.
            </summary>
            <param name="target">The target.</param>
            <param name="api">The API.</param>
            <param name="opcode">The opcode.</param>
            <param name="payload">The payload.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.SendAck(WhirlpoolCommunication.Packets.RevealPacket,NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Sends the ack.
            </summary>
            <param name="receivedPacket">The received packet.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.GetRevealAckPacket(WhirlpoolCommunication.Packets.RevealPacket,NTL.Reveal.RequestDataResult)">
            <summary>
            Gets the reveal ack packet.
            </summary>
            <param name="receivedPacket">The received packet.</param>
            <param name="requestDataResult">The request data result.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.Reveal.RevealHandler.MessageReceivedDelegate">
            <summary>
            The Message Received function delegate.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMSG">The received MSG.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.PublishRevealPacket(NTL.Reveal.WaitableRevealMessageQueue,NTL.Reveal.RevealHandler.MessageReceivedDelegate,System.Int32,NTL.Reveal.RequestDataResult)">
            <summary>
            Publishes the reveal packet.
            </summary>
            <param name="wrmq">WaitableRevealMessageQueue</param>
            <param name="messageReceived">The received message.</param>
            <param name="timeout">The timeout.</param>
            <param name="resquestResult">RequestDataResult.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandler.Dispose">
            <summary>
            Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
            </summary>
        </member>
        <member name="T:NTL.Reveal.RevealHandlerHelper">
            <summary>
            
            </summary>
        </member>
        <member name="M:NTL.Reveal.RevealHandlerHelper.GetNullableObject(System.Int32,System.Boolean)">
            <summary>
            Gets the nullable object.
            </summary>
            <param name="value">The value.</param>
            <param name="hasValue">if set to <c>true</c> [has value].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandlerHelper.GetNullableObject(System.Byte,System.Boolean)">
            <summary>
            Gets the nullable object.
            </summary>
            <param name="value">The value.</param>
            <param name="hasValue">if set to <c>true</c> [has value].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.RevealHandlerHelper.GetNullableObject(System.Boolean,System.Boolean)">
            <summary>
            Gets the nullable object.
            </summary>
            <param name="value">if set to <c>true</c> [value].</param>
            <param name="hasValue">if set to <c>true</c> [has value].</param>
            <returns></returns>
        </member>
        <member name="T:NTL.Reveal.WaitableRevealMessage">
            <summary>
            
            </summary>
            <seealso cref="T:NTL.WaitableMessage`1" />
        </member>
        <member name="F:NTL.Reveal.WaitableRevealMessage.source">
            <summary>
            The source
            </summary>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.Source">
            <summary>
            Gets or sets the source.
            </summary>
            <value>
            The source.
            </value>
        </member>
        <member name="F:NTL.Reveal.WaitableRevealMessage.destination">
            <summary>
            The destination
            </summary>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.Destination">
            <summary>
            Gets or sets the destination.
            </summary>
            <value>
            The destination.
            </value>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.API">
            <summary>
            Gets or sets the API.
            </summary>
            <value>
            The API.
            </value>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.IsFeedback">
            <summary>
            Get and Set if this message is a Feedback message (Cmd/fb = 1 set it true)
            Set null to ignore
            </summary>
            <value>
            <c>true</c> if this instance is feedback; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.IsFragmented">
            <summary>
            Get and Set if this message is a Fragmented message (frag = 1 set it true)
            Set null to ignore
            </summary>
            <value>
            <c>true</c> if this instance is fragmented; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.MoreMessagePending">
            <summary>
            Get and Set if this packet has more messages pending (MMP = 1 set it true)
            Set null to ignore
            </summary>
            <value>
              <c>true</c> if [more message pending]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.OpCode">
            <summary>
            Gets or sets the op code.
            Set null to ignore
            </summary>
            <value>
            The op code.
            </value>
        </member>
        <member name="F:NTL.Reveal.WaitableRevealMessage.payload">
            <summary>
            The payload
            </summary>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.PayLoad">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="F:NTL.Reveal.WaitableRevealMessage.payloadmask">
            <summary>
            The payloadmask
            </summary>
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessage.PayloadMask">
            <summary>
            Gets or sets the data mask.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessage.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.Reveal.WaitableRevealMessage" /> class.
            </summary>
            <param name="id">The identifier.</param>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessage.CompareTo(WhirlpoolCommunication.Packets.RevealPacket,System.Boolean)">
            <summary>
            Compares to the message incoming to the waitable message
            </summary>
            <param name="data">The data.</param>
            <param name="setMessageMatch">if set to <c>true</c> set message match if compare is true.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessage.FixBinaryMask">
            <summary>
            Fixes the binary mask.
            </summary>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessage.Copy">
            <summary>
            Copies this instance.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessage.ToString">
            <summary>
            Returns a <see cref="T:System.String" /> that represents this instance.
            </summary>
            <returns>
            A <see cref="T:System.String" /> that represents this instance.
            </returns>
        </member>
        <member name="T:NTL.Reveal.WaitableRevealMessageQueue">
            <summary>
            Waitable reveal message queue
            </summary>
            <seealso cref="T:NTL.WaitableMessageQueue`1" />
        </member>
        <member name="P:NTL.Reveal.WaitableRevealMessageQueue.RevealAck">
            <summary>
            Gets or sets the reveal ack.
            It's set if there is a API 1 Opcode 1 response in the queue.
            </summary>
            <value>
            The reveal ack.
            </value>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessageQueue.CompareTo(WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Compares the incoming message against the queue.
            Returns true if the message
            </summary>
            <param name="incomingMessage">The incoming message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.Reveal.WaitableRevealMessageQueue.ToString">
            <summary>
            Returns a <see cref="T:System.String" /> that represents this instance.
            </summary>
            <returns>
            A <see cref="T:System.String" /> that represents this instance.
            </returns>
        </member>
        <member name="T:NTL.NucleusHandler">
            <summary>
            Handles methods for APIs and its opcodes, label file parser, setting file and firmware download.
            Task Functions that return objects (not string or value/primitive types) will have properties that contains the 
            </summary>
        </member>
        <member name="F:NTL.NucleusHandler.agent">
            <summary>
            The agent
            </summary>
        </member>
        <member name="P:NTL.NucleusHandler.Agent">
            <summary>
            Gets or sets the agent.
            </summary>
            <value>
            The agent.
            </value>
        </member>
        <member name="P:NTL.NucleusHandler.Progress">
            <summary>
            Gets the progress.
            </summary>
            <value>
            The progress.
            </value>
        </member>
        <member name="F:NTL.NucleusHandler.acuDownloadSFIndex">
            <summary>
            The acu download sf index
            </summary>
        </member>
        <member name="F:NTL.NucleusHandler.RevealMaxSize">
            <summary>
            The reveal maximum size
            </summary>
        </member>
        <member name="F:NTL.NucleusHandler.api007DataFlashAlignment">
            <summary>
            The api007 data flash alignment
            </summary>
        </member>
        <member name="M:NTL.NucleusHandler.SetLogger(WhirlpoolCommunication.Utilities.Logger.ILogger)">
            <summary>
            Sets the logger.
            Set null to stop logging.
            </summary>
            <param name="logger">The logger.</param>
        </member>
        <member name="M:NTL.NucleusHandler.#ctor(WhirlpoolCommunication.IDevice,NTL.Reveal.RevealHandler,System.Boolean)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.NucleusHandler" /> class.
            Uses the instance of reveal handler provided by the class user.
            </summary>
            <param name="device">The IDevice device provides bare bone interface to a Whirlpool bus device, it exposes GetMessage, SendCommand and sendMessage members.</param>
            <param name="revealHandlerInstance">The reveal handler instance. Need to be initialized with disableGetMessage = true.</param>
            <param name="disableGetMessage">set to <c>true</c> [disable get message] if using your own message parsing</param>
            <example> The following example shows how to instantiate NTL dll in C#
            <code source="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Instatiating NTL and Widebox" /><para>Labview Example</para><para>Matlab Example</para></example>
        </member>
        <member name="M:NTL.NucleusHandler.#ctor(WhirlpoolCommunication.IDevice,System.Boolean)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.NucleusHandler"/> class.
            </summary>
            <param name="device">The IDevice device provides bare bone interface to a Whirlpool bus device, it exposes GetMessage, SendCommand and sendMessage members.</param>
            <param name="disableGetMessage">set to <c>true</c> [disable get message] if using your own message parsing</param>
            <example> The following example shows how to instantiate NTL dll in C#
            <code source ="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang ="C#" title ="C#"  region ="Instatiating NTL and Widebox"/>
            <para>Labview Example</para>
            <para>Matlab Example</para>
            </example>
        </member>
        <member name="P:NTL.NucleusHandler.RXTaskStatus">
            <summary>
            Gets the rx task status.
            </summary>
            <value>
            The rx task status.
            </value>
        </member>
        <member name="M:NTL.NucleusHandler.RXTask">
            <summary>
            Starts RXTask and gets the deviceLocal message and parses the extendedsimplewhirlpoolpacket message
            </summary>
        </member>
        <member name="M:NTL.NucleusHandler.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses ExtendedSimpleWhirlpoolPacket message.
            </summary>
            <param name="msg">IMessage is a public interface to synchronize device and SW messages.</param>
        </member>
        <member name="M:NTL.NucleusHandler.GetMaxPackageSize(System.Byte,System.Int32)">
            <summary>
            Request the maximum size of the reveal package.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout i. It is an optional parameter, by default it is set to 2s</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.GetMaxMessageSize" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRevealNodes(System.Byte,System.Int32)">
            <summary>
            Request the reveal nodes.
            A client can ask all the bus for who is available by issuing a broadcast command on opcode 1 (findRevealNodes) No parameters are required or it can issue a direct command for a specific node, the response is always a broadcast.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout. It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealNodes" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRevealApis(System.Byte,System.Int32)">
            <summary>
            Request available APIs in the Node/ACU.
            Will reply with a feedback containing list of its APIs.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout. It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealApis" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetApiInfo(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the API information.
            </summary>
            <param name="target">The target.</param>
            <param name="apiId">The API identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout. It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.ApiInfo" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetInstanceInfo(System.Byte,System.Int32)">
            <summary>
            Request Instances information.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout. It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.InstanceInfo" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetLoadData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request Load proccessed data.
            LOAD ID 0 to 254 is used to request specific LOAD ID data
            To request all load data<see cref="M:NTL.NucleusHandler.GetAllLoadData(System.Byte,System.Int32)" />
            </summary>
            <param name="target">The target.</param>
            <param name="loadID">The load identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.LoadData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllLoadData(System.Byte,System.Int32)">
            <summary>
            Gets all load data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AllLoadData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SubscribeToVariableData(System.Byte,System.UInt32,System.Action{System.Threading.Tasks.Task{NTL.OpcodesResultData.LoadData}})">
            <summary>
            Subscribes to variable data.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="callback">The callback.</param>
        </member>
        <member name="M:NTL.NucleusHandler.UnsubscribeToVariableData(System.Byte,System.UInt32)">
            <summary>
            Unsubscribes to variable data.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
        </member>
        <member name="M:NTL.NucleusHandler.GetLLIData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Request LLI data.
            LLI TYPE 0 to 254 is used to request specific LLI TYPE data
            LL POSITION Posotion of the LLI TYPE
            For requesting all the LLI Data <see cref="M:NTL.NucleusHandler.GetAllLLIData(System.Byte,System.Int32)" />
            LLI TYPE -255,LLI POSITION - Dont Care
            </summary>
            <param name="target">The target.</param>
            <param name="lliType">Type of the lli.</param>
            <param name="lliPosition">The lli position, its value should be >=1.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.LLIData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetLLIDataByGiId(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the lli data by gi identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="GiId">The gi identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllLLIData(System.Byte,System.Int32)">
            <summary>
            Gets all LLI data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AllLLIData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetHmiLLIData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the HMI lli data.
            </summary>
            <param name="target">The target.</param>
            <param name="lliType">Type of the lli.</param>
            <param name="lliPosition">The lli position.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllHmiLLIData(System.Byte,System.Int32)">
            <summary>
            Gets all HMI LLI data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetGIData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request GI Converted data.
            GI ID 0 to 254 is used to request specific GI ID converted data
            To request all GI data , refer GetALLGIData <see cref="M:NTL.NucleusHandler.GetAllLoadData(System.Byte,System.Int32)" />
            </summary>
            <param name="target">The target.</param>
            <param name="giID">The gi identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.GIData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllGIData(System.Byte,System.Int32)">
            <summary>
            Gets all GI data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AllGIData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetHmiGIData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the hmi gi data.
            </summary>
            <param name="target">The target.</param>
            <param name="gi">The gi, is the byte with GI ReadType and GI Position.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetHmiGIData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the hmi gi data.
            </summary>
            <param name="target">The target.</param>
            <param name="giType">Type of the gi.</param>
            <param name="giPosition">The gi position.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllHmiGIData(System.Byte,System.Int32)">
            <summary>
            Gets all HMI GI data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllLoadConfiguration(System.Byte,System.Int32)">
            <summary>
            Request to read the configuration of all LOAD.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
            Publishes all the LOAD ID and PILOT ID configured.
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllLLIConfiguration(System.Byte,System.Int32)">
            <summary>
            Request to read the configuration of all LLI
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
            Publishes all the LLI TYPE and LLI POSITION configured
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllGIConfiguration(System.Byte,System.Int32)">
            <summary>
            Request to read the configuration of all GI
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
            Publishes all the GI ID, LLI TYPE and LLI POSITION associated with each GI
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetHmiLLIConfiguration(System.Byte,System.Int32)">
            <summary>
            Gets the hmi lli configuration.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetHmiGIConfiguration(System.Byte,System.Int32)">
            <summary>
            Gets the hmi gi configuration.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetNumberOfCycle(System.Byte,System.Int32)">
            <summary>
            Request the number of cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.CycleNumberData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetStatusData(System.Byte,System.Int32)">
            <summary>
            Request the status data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.StatusData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRegulationsData(System.Byte,System.Int32)">
            <summary>
            Request  the regulations data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RegulationsData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetSystemMode(System.Byte,System.Int32)">
            <summary>
            Request the system mode.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SystemMode" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRegulationById(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the regulation by identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="functionId">The function identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RegulationById" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetStatusStructure(System.Byte,System.Int32)">
            <summary>
            Request the status structure.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.StatusStructure" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetFunctionsId(System.Byte,System.Int32)">
            <summary>
            Gets the functions identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.FunctionsId" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetCycleNames(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the cycle names.
            Publish the Cycle Names for all the cycles configured in the setting file on the ACU in a given compartment.
            Only the cycle names for the cycles configured in the Selector regulation table are reported since the other cycles would not be 
            selectable through the selector regulation. The position of the Cycle Name in the payload correlates to the Selector regulation
            index to use to select the cycle with that Cycle Name. So, the first Cycle Name will be the cycle at index 1 of the Selector regulation. 
            The second Cycle Name will be the cycle at index 2 of the Selector regulation, and so on.
            </summary>
            <param name="target">The target.</param>
            <param name="compartment">Compartment Index (0-N);.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetFaultCode(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the saved fault code.
            A client can request fault codes associated with stored faults. Which fault codes are requested depends on the specified fault index.
            If the Fault Index = 0, the server will send the most recently detected fault.
            If the Fault Index = 1, the server will send the second most recently detected fault, etc.
            For all saved fault codes(Fault Index = 255), <see cref="M:NTL.NucleusHandler.GetAllStoredFaultCodes(System.Byte,System.Int32)" />.
            </summary>
            <param name="target">The target.</param>
            <param name="faultIndex">The fault reference.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SavedFaultCode" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAllStoredFaultCodes(System.Byte,System.Int32)">
            <summary>
            Gets all stored fault codes(FaultIndex = 255), the server will send all the stored faults. If there are no faults stored, then the server will still respond with a message, but the payload will be empty.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AllSavedFaultCodes" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetDiagnosticsConfig(System.Byte,System.Int32)">
            <summary>
            Gets the diagnostics configuration.
            A client can request information about how the diagnostic information is organized. The server will respond by publishing diagnostic configuration information. The diagnostic configuration information is arranged in pairs of bytes where each pair represents a section of the statistics data. The first byte of each pair is the number of blocks in the section. The second byte of each pair is the number of bytes in each block. For example:
            Byte 1 = Number of data blocks in the 1st section
            Byte 2 = Size of a data block in the 1st section
            Byte 3 = Number of data blocks in the 2nd section
            Byte 4 = Size of a data block in the 2nd section etc.
            Refer to the Statistics data for a definition of each section.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetStatisticsData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the statistics data.
            </summary>
            <param name="target">The target.</param>
            <param name="requestedSection">The requested section.Range is from 1-7 and 255 to get all the sections data </param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetApplianceData(System.Byte,System.Int32)">
            <summary>
            Request the appliancedata.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="M:NTL.NucleusHandler.ApplianceData(System.Byte,System.String,System.String,System.Byte,System.Int32)" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetBoardData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the board data.
            </summary>
            <param name="target">The target.</param>
            <param name="boardIndex">Index of the board.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="M:NTL.NucleusHandler.BoardData(System.Byte,System.Byte,System.String,System.String,System.String,System.Byte,System.Byte,System.Int32)" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetProjectData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the project data.
            </summary>
            <param name="target">The target.</param>
            <param name="boardIndex">Index of the board.</param>
            <param name="projectIndex">Index of the project.
            Firmware - 0; Touch - 1; SettingFile - 254; Not Available - 255</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.ProjectData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetServiceData(System.Byte,System.Int32)">
            <summary>
            Request the service data.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.ServiceData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetFVTData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the FVT data.
            </summary>
            <param name="target">The target.</param>
            <param name="fvtIndex">Index of the FVT.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="M:NTL.NucleusHandler.FVTData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32)" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetEOLData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the EOL(End of Line) data by Index.
            </summary>
            <param name="target">The target.</param>
            <param name="eolIndex">Index of the eol.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="M:NTL.NucleusHandler.EOLData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32)" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetCalibrationdData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request Calibration data.
            </summary>
            <param name="target">The target.</param>
            <param name="calibrationDataId">The calibration data identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.CalibrationdData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetClassBSignature(System.Byte,System.Int32)">
            <summary>
            Request the class B signature.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.ClassBSignature" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileInfo(System.Byte,System.Int32)">
            <summary>
            Request the setting file information.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileInfo" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileFlashAlignment(System.Byte,System.Int32)">
            <summary>
            Request the setting file flash alignment.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileFlashAlignment" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileInfoById(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the setting file information by identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="settingFileId">The setting file identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileInfoById" />
            </returns>
            <remarks>
            Sequence diagram: <br /><img src="../API007Data_SF_Section.png" />
            </remarks>
        </member>
        <member name="M:NTL.NucleusHandler.GetHMISettingFileData(System.Byte,System.Byte[],System.Byte,System.Int32)">
            <summary>
            Gets the hmi setting file data.
            </summary>
            <param name="target">The target.</param>
            <param name="offset">The offset.</param>
            <param name="size">The size.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.HMISettingFileData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileDataById(System.Byte,System.Byte,System.Int16,System.Int16,System.Int32)">
            <summary>
            Gets the setting file data by identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="settingFileId">The setting file identifier.</param>
            <param name="offset">The offset.</param>
            <param name="size">The size.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileDataById" />
            </returns>
            <remarks>
            Sequence diagram: <br /><img src="../API007Data_SF_Section.png" />
            </remarks>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileDisplacementInfo(System.Byte,System.Int16,System.Int16,System.Int32)">
            <summary>
            Gets the setting file displacement information.
            </summary>
            <param name="target">The target.</param>
            <param name="pointerId">The pointer identifier.</param>
            <param name="displacement">The displacement.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileDisplacementInfo" />
            </returns>
            <remarks>
            Sequence diagram: <br /><img src="../API007Data_SF_Displacement.png" />
            </remarks>
        </member>
        <member name="M:NTL.NucleusHandler.GetSettingFileDisplacementData(System.Byte,System.Int16,System.Int16,System.Int16,System.Byte,System.Int32)">
            <summary>
            Gets the setting file displacement data.
            </summary>
            <param name="target">The target.</param>
            <param name="pointerId">The pointer identifier.</param>
            <param name="displacement">The displacement.</param>
            <param name="offset">The offset.</param>
            <param name="displacementSize">Size of the displacement.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SettingFileDisplacementData" />
            </returns>
            <remarks>
            Sequence diagram: <br /><img src="../API007Data_SF_Displacement.png" />
            </remarks>
        </member>
        <member name="M:NTL.NucleusHandler.RequestSpecificVariable(System.Byte,System.Byte,NTL.OpcodesResultData.VariableDataTypes,System.Int32,System.Boolean,System.Int32)">
            <summary>
            Request the data for a specific fixed or memorymapped variable.
            </summary>
            <param name="target">The target.</param>
            <param name="variableId">The variable identifier.</param>
            <param name="dataType">Type of the data.</param>
            <param name="offSet">The off set.</param>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian],by default it is set to true because all the platform microcontrollers are based on littleendian.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.SpecificVariable" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestFixedVariableMetadata(System.Byte,System.Byte,System.Int32)">
            <summary>
            Request the metadata of a fixed variable.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.FixedVariableMetadata" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestAllFixedVariableMetadata(System.Byte,System.Int32)">
            <summary>
            Requests all fixed variable metadata.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestAcquisitionConfiguration(System.Byte,System.Int32)">
            <summary>
            Request the current configuration of the data acquisition.
            This command may be enabled or disabled in the firmware at compile time.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AcquisitionConfiguration" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestNumberOfVariables(System.Byte,System.Int32)">
            <summary>
            Request the number of fixed variables and memory mapped variables that are supported by the firmware.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.NumberOfVariables" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SubscribeToVariable(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Subscribes to variable.
            </summary>
            <param name="target">The target.</param>
            <param name="api">The API.</param>
            <param name="opcode">The opcode.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
        </member>
        <member name="M:NTL.NucleusHandler.UnsubscribeToVariable(System.Byte)">
            <summary>
            Unsubscribes  variable.
            </summary>
            <param name="target">The target.</param>
        </member>
        <member name="M:NTL.NucleusHandler.SendHearbeat">
            <summary>
            Sends the hearbeat.
            This message is periodically sent by REVEAL. This allows nodes, which have registered for events to maintain confidence in the event sources. In other words, Heartbeat insures connection integrity. Publish Heartbeat will not be sent until after REVEAL receives a command. This can be used to prevent the Traffic Storm condition during power up. Publish Heartbeat will be suspended after a Clear Events message is received, but will resume after the next subsequent command.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishWakeup">
            <summary>
            Publishes the wakeup.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetWakeUpAckList(System.Byte,System.Int32)">
            <summary>
            Gets the board list.
            </summary>
            <param name="ignoreNode">The ignore node.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SimulateHeartbeat(System.UInt16)">
            <summary>
            Simulates the hearbeat.
            </summary>
            <param name="heartbeatPeriod">The heartbeat period.</param>
            <param name="cancellationToken">The cancellation token.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopHeartBeat">
            <summary>
            Stops the heart beat.
            </summary>
        </member>
        <member name="M:NTL.NucleusHandler.SetLoad(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sets the load. In order to set a load, first step is change from Supervisor mode to external control mode using SetSystemMode method OR use <see cref="M:NTL.NucleusHandler.EnablePCControl(System.Byte,System.UInt16,System.Int32)" /> .
            Load ID = 0 to 254 is used to set the individual load
            Load ID = 255 is used to turnoff all the loads.In this case following payload value is invalid <see cref="M:NTL.NucleusHandler.SetAllLoadOff(System.Byte,System.Int32)" />
            </summary>
            <param name="target">The target.</param>
            <param name="loadId">Id of the load.</param>
            <param name="loadData">The load data.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
            <example> The following example shows to set a load in C#
            <code source ="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Set Load example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.SetLoad(System.Byte,System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sets the load. In order to set a load, first step is change from Supervisor mode to external control mode using SetSystemMode method OR use <see cref="M:NTL.NucleusHandler.EnablePCControl(System.Byte,System.UInt16,System.Int32)" /> .
            Load ID = 0 to 254 is used to set the individual load
            Load ID = 255 is used to turnoff all the loads.In this case following payload value is invalid <see cref="M:NTL.NucleusHandler.SetAllLoadOff(System.Byte,System.Int32)" />
            </summary>
            <param name="target">The target.</param>
            <param name="loadId">The load identifier.</param>
            <param name="loadSize">Size of the load.</param>
            <param name="loadData">The load data.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
            <example> The following example shows to set a load in C#
            <code source="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Set Load example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.SetMultipleLoads(System.Byte,NTL.OpcodesResultData.LoadData[],System.Int32)">
            <summary>
            Sets the multiple loads.
            </summary>
            <param name="target">The target.</param>
            <param name="loadData">To set multiple loads, just provide loadId and loadData for the required loads. This function will get the other information about the loads, refer <see cref="M:NTL.NucleusHandler.GetLoadsInfo(System.Byte,System.Byte[])" /> to get all the available loads information</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
            <example> The following example shows to set multiple loads in C#
            <code source ="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Set multiple loads" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.GetLoadsInfo(System.Byte,System.Byte[])">
            <summary>
            Gets the loads information.
            </summary>
            <param name="target">The target.</param>
            <param name="loadIds">The load ids.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetAllLoadOff(System.Byte,System.Int32)">
            <summary>
            Set all load off.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetDebugLabel(System.Byte,System.Byte,System.String,System.Int32)">
            <summary>
            Set the debuglabel using debug function Index and label.
            </summary>
            <param name="target">The target.</param>
            <param name="debugFunctionIndex">Index of the debug function.</param>
            <param name="label">The label.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetDebugVariable(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Set the debug variable by debug function index and variable value.
            </summary>
            <param name="target">The target.</param>
            <param name="debugFunctionIndex">Index of the debug function.</param>
            <param name="varaiableValue">The varaiable value.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetHMIObject(System.Byte,System.Byte,System.UInt16,System.UInt16,System.Int32)">
            <summary>
            Set the HMI object by providing object type, object index and object value
            </summary>
            <param name="target">The target.</param>
            <param name="objectType">Type of the object.</param>
            <param name="objectIndex">Index of the object.</param>
            <param name="objectValue">The object value.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.PlayHMISound(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Play the HMI sound by providing sound index and volume.
            </summary>
            <param name="target">The target.</param>
            <param name="soundIndex">Index of the sound.</param>
            <param name="volume">The volume.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetTestStorage(System.Byte,System.Byte,System.Int32)">
            <summary>
            Set the test storage.
            </summary>
            <param name="target">The target.</param>
            <param name="storage">The storage.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.EngageTestCycle(System.Byte,NTL.OpcodesResultData.TestCycles,System.Int32)">
            <summary>
            Engage the test cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="testCycle">Valid inputs are 0 (EOL Test #0), 1 (EOL Test #1) or 2 (EOL Test #2) ,3 (Service Test #0) or 4 (Service Test #1)</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.PhaseTestCycle(System.Byte,System.Byte,System.Int32)">
            <summary>
            Set the test cycle phase.
            </summary>
            <param name="target">The target.</param>
            <param name="testPhaseCycle">Valid inputs are 255 (0xFF): PHASE_STEP_FORWARD,254 (0xFE): PHASE_STEP_BACKWARD,253 (0xFD): PHASE_STEP_NONE,0 - number of phases in cycle: Go to specific phase.</param>
            Note: If at the last phase of the test cycle and PHASE_STEP_FORWARD is commanded the test cycle will end.
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetExtractLoad(System.Byte,System.Byte,System.Int32)">
            <summary>
            Set the extract load state.
            </summary>
            <param name="target">The target.</param>
            <param name="extractLoadState">State of the extract load.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetExtractGIs(System.Byte,System.Byte,System.Int32)">
            <summary>
            Set the extract GI state.
            </summary>
            <param name="target">The target.</param>
            <param name="extractGIsState">Extract GIs state.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.CallDebugFunction(System.Byte,System.Byte,System.Int32)">
            <summary>
            Call debug function.
            </summary>
            <param name="target">The target.</param>
            <param name="debugFunctionIndex">Index of the debug function.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.JumpToStep(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Jumps to step: To change the step in a phase of a Cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="compartment">The compartment.</param>
            <param name="testCycleStep">The test cycle step. 
            Valid inputs are:
            255 (0xFF): PHASE_STEP_FORWARD
            254 (0xFE): PHASE_STEP_BACKWARD
            253 (0xFD): PHASE_STEP_NONE
            0 - number of steps in phase: Go to specific step.</param>
            Note: If at the last step of a phase and PHASE_STEP_FORWARD is commanded, the Interpreter will skip to step 0 of the next phase. If the next phase does not exist the test cycle will end.
            Note: If at step 0 of a phase and PHASE_STEP_BACKWARD is commanded, the Interpreter will go to the last step of the previous phase if the previous phase exists.
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StartMotorAPI05(System.Byte,System.UInt16,System.UInt16,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Starts the motor using API05.
            </summary>
            <param name="target">The target.</param>
            <param name="velocity">The velocity.</param>
            <param name="acceleration">The acceleration.</param>
            <param name="tappedFieldActivationThreshold">The tapped field activation threshold.</param>
            <param name="padding">The padding.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopMotorAPI05(System.Byte,System.UInt16,System.Int32)">
            <summary>
            Stops the motor using API05.
            </summary>
            <param name="target">The target.</param>
            <param name="decelerationRate">The deceleration rate.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetSystemMode(System.Byte,NTL.OpcodesResultData.EnumModeType,NTL.OpcodesResultData.EnumSubModeType,System.Int32)">
            <summary>
            Set the system mode.
            </summary>
            <param name="target">The target.</param>
            <param name="mode">The mode.</param>
            <param name="subMode">The sub mode.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetRegulations(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Set the regulations.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="regulations">The regulations.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetHeartBeat(System.Byte,System.Int32)">
            <summary>
            Sets the heart beat.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.EnablePCControl(System.Byte,System.UInt16,System.Int32)">
            <summary>
            Enables PC control mode. This function has to be called only once for example it shouldn't be in a while loop.
            Note: Always call disbalePC control before EnablePCcontrol in order to avoid multiple EnablePCcontrol threads running
            which will create traffic in the WIN bus by sending the heartbeat signal from multiple threads.
            </summary>
            <param name="target">The target.</param>
            <param name="heartbeatPeriod">The timeout is in msecs. ACU gets back to supervisor mode in 30s, so the timeout should be atleast 2 times faster than 30s. Recommended value is 10s.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.DisablePCControl(System.Byte,System.Int32)">
            <summary>
            Disables PC ccontrol mode.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetApplianceData(System.Byte,System.String,System.String,System.Byte,System.Int32,System.Boolean)">
            <summary>
            Sets the appliance data.
            </summary>
            <param name="target">The target.</param>
            <param name="modelNumber">The model number.</param>
            <param name="serialNumber">The serial number.</param>
            <param name="numberOfBoards">The number of boards.</param>
            <param name="autoStore">if set to <c>true</c> automatic call StoreStaticdata.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ApplianceData(System.Byte,System.String,System.String,System.Byte,System.Int32)">
            <summary>
            Sets the appliance data.
            </summary>
            <param name="target">The target.</param>
            <param name="modelNumber">The model number.</param>
            <param name="serialNumber">The serial number.</param>
            <param name="numberOfBoards">The number of boards.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetBoardData(System.Byte,System.Byte,System.String,System.String,System.String,System.Byte,System.Byte,System.Int32,System.Boolean)">
            <summary>
            Sets the board data.
            </summary>
            <param name="target">The target.</param>
            <param name="boardIndex">Index of the board.</param>
            <param name="boardPartNumber">The board part number.</param>
            <param name="boardRevision">The board revision.</param>
            <param name="boardSerialNumber">The board serial number.</param>
            <param name="boardReplacment">The board replacment.</param>
            <param name="boardNumberOfProjects">The board number of projects.</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.BoardData(System.Byte,System.Byte,System.String,System.String,System.String,System.Byte,System.Byte,System.Int32)">
            <summary>
            Sets the board data.
            </summary>
            <param name="target">The target.</param>
            <param name="boardIndex">Index of the board.</param>
            <param name="boardPartNumber">The board part number.</param>
            <param name="boardRevision">The board revision.</param>
            <param name="boardSerialNumber">The board serial number.</param>
            <param name="boardReplacment">The board replacment.</param>
            <param name="boardNumberOfProjects">The board number of projects.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetServiceData(System.Byte,System.Byte,System.String,System.String,System.String,System.String,System.String,System.Int32)">
            <summary>
            Sets the serice data.
            </summary>
            <param name="target">The target.</param>
            <param name="serviceTesterId">The service tester identifier.</param>
            <param name="serviceTesterVersion">The service tester version.</param>
            <param name="serviceTestDate">The service test date.</param>
            <param name="serviceTestAge">The service test age.</param>
            <param name="serviceTestDuration">Duration of the service test.</param>
            <param name="serviceTestResult">The service test result.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetFVTData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32,System.Boolean)">
            <summary>
            Sets the FVT data.
            </summary>
            <param name="target">The target.</param>
            <param name="fvtIndex">Index of the FVT.</param>
            <param name="fvtId">The FVT identifier.</param>
            <param name="fvtTesterVersion">The FVT tester version.</param>
            <param name="fvtTestDate">The FVT test date.</param>
            <param name="fvtTestResult">The FVT test result.</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.FVTData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32)">
            <summary>
            Sets the FVT data.
            </summary>
            <param name="target">The target.</param>
            <param name="fvtIndex">Index of the FVT.</param>
            <param name="fvtId">The FVT identifier.</param>
            <param name="fvtTesterVersion">The FVT tester version.It should be of 3 bytes long</param>
            <param name="fvtTestDate">The FVT test date.It should be of 8 bytes long</param>
            <param name="fvtTestResult">The FVT test result.It should be of 16 bytes long</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetFVTDataBytes(System.Byte,System.Byte,System.String,System.String,System.Int32,System.Boolean)">
            <summary>
            Sets the FVT data bytes.
            </summary>
            <param name="target">The target.</param>
            <param name="fvtIndex">Index of the FVT.</param>
            <param name="fvtTestResult">The FVT test result.</param>
            <param name="fvtTestResultMask">The FVT test result mask.</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.FVTDataBytes(System.Byte,System.Byte,System.String,System.String,System.Int32)">
            <summary>
            Sets the FVT data bytes.
            </summary>
            <param name="target">The target.</param>
            <param name="fvtIndex">Index of the FVT.</param>
            <param name="fvtTestResult">The FVT test result.</param>
            <param name="fvtTestResultMask">The FVT test result mask.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetCalibrationData(System.Byte,System.Byte,System.Byte[],System.Int32,System.Boolean)">
            <summary>
            Sets the calibration data.
            </summary>
            <param name="target">The target.</param>
            <param name="calibrationId">The calibration identifier.</param>
            <param name="calibrationData">The calibration data.The size of the calibration data vary depending on the ID and product</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.CalibrationData(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sets the calibration data.
            </summary>
            <param name="target">The target.</param>
            <param name="calibrationId">The calibration identifier.</param>
            <param name="calibrationData">The calibration data. The size of the calibration data vary depending on the ID and product</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetEOLData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32,System.Boolean)">
            <summary>
            Sets the eol data.
            </summary>
            <param name="target">The target.</param>
            <param name="eolIndex">Index of the eol.</param>
            <param name="eolId">The eol identifier.</param>
            <param name="eolTesterVersion">The eol tester version.</param>
            <param name="eolTestDate">The eol test date.</param>
            <param name="eolTestResult">The eol test result.</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.EOLData(System.Byte,System.Byte,System.Byte,System.Byte[],System.String,System.Byte[],System.Int32)">
            <summary>
            Sets the eol data.
            </summary>
            <param name="target">The target.</param>
            <param name="eolIndex">Index of the eol.</param>
            <param name="eolTesterId">The eol tester identifier.</param>
            <param name="eolTesterVersion">The eol tester version.</param>
            <param name="eolTestDate">The eol test date.</param>
            <param name="eolTestResult">The eol test result.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetEOLDataBytes(System.Byte,System.Byte,System.String,System.String,System.Int32,System.Boolean)">
            <summary>
            Sets the eol data bytes.
            </summary>
            <param name="target">The target.</param>
            <param name="eolIndex">Index of the eol.</param>
            <param name="eolTestResult">The eol test result.</param>
            <param name="eolTestResultMask">The eol test result mask.</param>
            <param name="autoStore">if set to <c>true</c> [automatic store].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.EOLDataBytes(System.Byte,System.Byte,System.String,System.String,System.Int32)">
            <summary>
            Sets the eol data bytes.
            </summary>
            <param name="target">The target.</param>
            <param name="eolIndex">Index of the eol.</param>
            <param name="eolTestResult">The eol test result.</param>
            <param name="eolTestResultMask">The eol test result mask.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.StoreStaticData(System.Byte,System.Int32)">
            <summary>
            Stores the staticdata.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetSafetyRelevantConditions(System.Byte,System.Byte,System.Byte,System.Byte,System.Byte[],System.Int32,System.Int32,System.Int32)">
            <summary>
            Sets the Safety conditions.
            </summary>
            <param name="target">The target/Destination Address  is the address of the microcontroller that was expected to receive the API020 message.</param>
            <param name="sourceAddress">The source address is the address of the microcontroller that was expected to transmit the API020 message. It should be same as CCB2 address or 14 otherwise ACU will reject the message</param>
            <param name="opcode">The opcode, platform specific opcode.</param>
            <param name="dataSize">Size of the data per message. If data lenght is bigger than dataSize, it will split the data in more messages then send in all slipted based on the given size.</param>
            <param name="data">The data is the Class B data that is being transmitted across a Class A communication bus. The maximum size of this data is 11 bytes in order to ensure that single-bit and double-bit communication errors can be detected. Longer messages will be ignored by API020.</param>
            <param name="period">The period.</param>
            <param name="offset">The offset.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopSRConditions(System.Byte)">
            <summary>
            Stops the Safety conditions.
            </summary>
            <param name="target">The target.</param>
        </member>
        <member name="M:NTL.NucleusHandler.SetEraseFlash(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sets the erase flash.
            </summary>
            <param name="target">The target.</param>
            <param name="addressRange">The address range.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetWriteFlash(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Sets the write flash.
            </summary>
            <param name="target">The target.</param>
            <param name="addressRange">The address range.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetForceReset(System.Byte,System.Int32,NTL.OpcodesResultData.ResetMode,System.Boolean,System.Int32)">
            <summary>
            Sets the force reset.
            </summary>
            <param name="target">The target.</param>
            <param name="millisecondsTimeout">The milliseconds timeout.</param>
            <param name="resetMode">The reset mode.</param>
            <param name="waitForReset">if set to <c>true</c> [wait for reset].</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestLowPowerMode(System.Byte,System.UInt32,System.Int32)">
            <summary>
            Requests the low power mode.
            </summary>
            <param name="target">The target.</param>
            <param name="sleepTimer">The sleep timer.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestWakeSystem(System.Byte,System.Int32)">
            <summary>
            Requests the wake system.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.EnablePeriodicData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Enable or disable periodic publication of selected variables.
            </summary>
            <param name="target">The target.</param>
            <param name="startOrStop">The start or stop.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.DeselectAllVariables(System.Byte,System.Int32)">
            <summary>
            Remove all fixed variables and all memorymapped variables from the periodic publication list.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SelectAllVariables(System.Byte,System.Int32)">
            <summary>
            Add all fixed variables and all defined memorymapped variables to the periodic publication list.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.DeselectSpecificVariables(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Remove the specified fixed variables and memorymapped variables from the periodic publication list.
            </summary>
            <param name="target">The target.</param>
            <param name="indices">The indices.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SelectSpecificVariables(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Add the specified fixed variables and memorymapped variables to the periodic publication list.
            </summary>
            <param name="target">The target.</param>
            <param name="indices">The indices.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetupPeriodicPublication(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Specify the publication method used to publish the periodic data.
            Specify the millisecond period between publication of data streams.
            </summary>
            <param name="target">The target.</param>
            <param name="method">The method.</param>
            <param name="milliSecondPeriod">The milli second period. Big endian bytes of a ushort value.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetupPeriodicPublication(System.Byte,NTL.OpcodesResultData.SetExtractionMethod,System.UInt16,System.Int32)">
            <summary>
            Specify the publication method used to publish the periodic data.
            Specify the millisecond period between publication of data streams.
            </summary>
            <param name="target">The target.</param>
            <param name="method">The method.</param>
            <param name="milliSecondPeriod">The milli second period.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.DefineMemoryMappedVariable(System.Byte,System.Byte,System.Byte,System.Int32,System.Int32)">
            <summary>
            Specify the address and size of a memory mapped variable.
            Note: This does not select the memory mapped variable for periodic publication.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.It can be any number which are not used for fixed variable Ids</param>
            <param name="size">The size.</param>
            <param name="address">The address.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.UndefineMemoryMappedVariable(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Clear an previously defined address and size from the specified memory mapped variable(s).
            If the first Index is 0xFF, then all memory mapped variables are cleared.
            </summary>
            <param name="target">The target.</param>
            <param name="indices">The indices.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ConfigureOnChangeBehavior(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Configure whether a fixed variable or a memory mapped variable should be published on change.
            If Index = 0xFF, then the requested configuration applies to all variables.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="onChangeBehavior">The on change behavior.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WriteFixedBehavior(System.Byte,System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Write data to one or more array elements of a fixed variable.
            The fixed variable must be writable.The data to write must fit in the variable data space.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="arrayposition">The arrayposition.</param>
            <param name="value">The value.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" /></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RequestTouchData(System.Byte,System.Byte,System.Byte,System.UInt16,System.Int32)">
            <summary>
            Gets the touch data.
            </summary>
            <param name="target">The target.</param>
            <param name="deviceId">The device identifier.</param>
            <param name="requestKeyId">The request key identifier.</param>
            <param name="broadcastInMilliseconds">The broadcast in milliseconds.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitTouchData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the touch data.
            </summary>
            <param name="target">The target.</param>
            <param name="deviceId">The device identifier.</param>
            <param name="requestKeyId">The request key identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopTouchData(System.Byte,System.Byte,System.Int32)">
            <summary>
            Stops the publishing touch data.
            </summary>
            <param name="target">The target.</param>
            <param name="deviceId">The device identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GenerateFault(System.Byte,System.Byte[],System.Int32)">
            <summary>
            Generates a fault remotely if the fault is configured correctly.
            The External Fault Key must be defined in the cross-category configuration of the API018 firmware.
            The External Fault Key must be mapped to a category-specific Fault ID in the API018 firmware configuration.
            The category-specific Fault ID must have a behavior configured through the setting file.
            </summary>
            <param name="target">The target.</param>
            <param name="externalFaultKey">The external fault key.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ClearSavedFaults(System.Byte,System.Int32)">
            <summary>
            Clears the saved faults.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetupVariableStream(System.Byte,NTL.OpcodesResultData.VariableInfo[],NTL.OpcodesResultData.SetExtractionMethod,System.Boolean,System.Boolean,System.UInt16)">
            <summary>
            Setup the variables stream data.
            </summary>
            <param name="target">The target.</param>
            <param name="variableStreamInfo">The variable stream information, refer <see cref="T:NTL.OpcodesResultData.VariableInfo"/>.</param>
            <param name="method">The method, refer <see cref="T:NTL.OpcodesResultData.SetExtractionMethod" /></param>
            <param name="onChangeBehavior">if set to <c>true</c> [on change behavior].</param>
            <param name="isPeriodic">if set to <c>true</c> [is periodic].</param>
            <param name="milliSecondPeriod">The milli second period.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetVariableStreamData(System.Byte,NTL.OpcodesResultData.VariableInfo[],System.Boolean,System.Int32)">
            <summary>
            Streams the selected variable data in the bus. Make sure to Setup the stream data using SetupVariableStream function<see cref="M:NTL.NucleusHandler.SetupVariableStream(System.Byte,NTL.OpcodesResultData.VariableInfo[],NTL.OpcodesResultData.SetExtractionMethod,System.Boolean,System.Boolean,System.UInt16)" />
            </summary>
            <param name="target">The target.</param>
            <param name="variableStreamInfo">The variable stream information.</param>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian], by default it is set to true because all the platform microcontrollers are based on littleendian.</param>
            <param name="timeout">It is in mSecs and by default it is set 2000. Change it as per your streamrate if required.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.VariableStreamData" />
            </returns>
            <example> The following example shows to use getvariableStreamdata function of NTL in C#
            <code source = "..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="API10 variable stream example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.GetFailureFlags(System.Byte,System.Byte,System.Int32)">
            <summary>
            Publish the failure flags reported by the specified motor control.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.FailureFlags" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetMotorStatus(System.Byte,System.Byte,System.Int32)">
            <summary>
            Publish the status flags reported by the specified motor control.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.MotorStatus" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetEvent(System.Byte,System.Byte,System.Int32)">
            <summary>
            Events are generated by each motor or device in the system. The motor controller generates the events as they occur.
            Each time an event is generated, an event(<see cref="T:NTL.OpcodesResultData.Event" />) message is sent to the Client. There are standard events that every motor or device can generate.
            Any motor controller can define additional platformspecific events.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.PublishEvent" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAnalogData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Publish the requested analog data value.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="analogChannel">The analog channel.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.AnalogData" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetPeriodicDataStatus(System.Byte,System.Int32)">
            <summary>
            Publish the status of the periodic data publication.A 32bit Analog Channels Bitmap is published for each motor that is controlled by the server.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.PeriodicDataStaus" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.StartMotorFVT(System.Byte,System.Byte,System.Int32)">
            <summary>
            Starts the motor FVT.
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.StartMotorFVTResult" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopMotorFVT(System.Byte,System.Byte,System.Int32)">
            <summary>
            Stop the motor FVT.
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.StopMotorFVTResult" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetMotorFVTResults(System.Byte,System.Byte,System.Int32)">
            <summary>
            Get the motor FVT results.
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.GetMotorFVTResult" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.StartAndGetMotorFVTResults(System.Byte,System.Byte,System.Int32)">
            <summary>
            Start FVT Motor.
            Returns both Start and Get Motor FVT result messages.
            Wait until Start and Get results are automatically published OR Timeout after 15 seconds from start results and request get results
            No need to stop Motor FVT. Once Motor FVT starts, Motor FVT finishes itself.
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="timeout">The timeout, by default it is set to 15s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.StartAndGetMotorFVTResult" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetMCIErrorResults(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Get MCI error results
            MCI Error Command 0 -  read then publishes errors from MCI
            MCI Error Command 255 - clears, reads and then publishes errors from MCI
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="mciErrorCommand">The mci error command.</param>
            <param name="timeout">The timeout(ms).The function will send timeout error if it doesn't receive message from the ACU within the set timeout . It is an optional parameter, by default it is set to 2s.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.GetMCIErrorResult" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopMotor(System.Byte,System.Byte,System.UInt16,System.Int32)">
            <summary>
            Stop the motor and/or the mechanically controlled device. Cancel the AutoStart feature timer.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor index/ Id.</param>
            <param name="decelerationRate">The deceleration rate in rpm/s.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RunMotor(System.Byte,System.Byte,System.Int16,System.UInt16,System.Int32)">
            <summary>
            Runs the motor and/or the mechanically controlled device. The Target Velocity and Acceleration can describe either the motor or the mechanically controlled device(e.g.drum).
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="velocity">The velocity in rpm.</param>
            <param name="acceleration">The acceleration in rpm/s.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.KeepRunningMotor(System.Byte,System.Byte,System.Int32)">
            <summary>
            Restart the timer for the autostopfeature.The motor controller can be configured with the AutoStop feature enabled.The AutoStop
            feature will automatically stop the motor if a configurable time period has expired after the last motor command.The motor commands that restart the
            period are OpCode 3 (API221_CMD_KEEP_RUNNING), OpCode 5 (API221_CMD_RUN), and OpCode 6(API221_CMD_SET_MOTION_BEHAVIOR). The AutoStart
            feature is cancelled if OpCode 4 (API221_CMD_STOP) is sent and acknowledged.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.ClearFailureFlags(System.Byte,System.Byte,System.Int32)">
            <summary>
            Clear the failure flags that can be cleared for the specified motor control.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetMotionBehavior(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Select the Motion Behavior that the motor (or the mechanically controlled device) should execute. A Motion Behavior is a platformspecific
            behavior that could involve multiple start and stop commands.Each Motion Behavior must have one(1) or more Behavior Parameters associated with it.
            Specific implementation of this command is optional and platformspecific.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="behaviorParameters">The behavior parameters.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetDataPublicationPeriod(System.Byte,System.UInt16,System.Int32)">
            <summary>
            Set the number of milliseconds between periodic publications of data specified by the Add Periodic Data Channels OpCode.
            There can only be one publication rate for all motor controllers on a communication node.
            Setting this value to zero (0) will disable periodic publication of data..
            </summary>
            <param name="target">The target.</param>
            <param name="period">The period.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.AddPeriodicChannels(System.Byte,System.Byte,System.Boolean[],System.Int32)">
            <summary>
            Add a set of analog data channels related to a motor controller to the list of analog data that is published periodically.
            A 1 in bit position n of the Analog Channels Bitmap indicates that Analog Data Channel n should be added to the list.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="analogChannelsBitmap">The analog channels bitmap.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.RemovePeriodicChannels(System.Byte,System.Byte,System.Boolean[],System.Int32)">
            <summary>
            Removes the periodic channels.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="analogChannelsBitmap">The analog channels bitmap.</param>
            <param name="timeout">The timeout.</param>
            <returns>
              <see cref="T:NTL.OpcodesResultData.RevealAck" />
            </returns>
        </member>
        <member name="M:NTL.NucleusHandler.Wash(System.Byte,System.Byte,System.UInt16,System.UInt16,System.Int16,System.UInt16,System.UInt16,System.Int32)">
             <summary>
             The Client can request that the motor run forward and backward repeatedly by sending the API221_CMD_WASH command to the Server that controls the motor.
            The wash command specifies the on time, the off time, the target velocity, the acceleration rate, and the deceleration rate to use while washing.
            If the Server does not implement the API221_DEVICE_WASH() macro, then the API221_CMD_WASH OpCode is not supported.
             </summary>
             <param name="target">The target.</param>
             <param name="motorId">The motor identifier.</param>
             <param name="onTime">The on time.</param>
             <param name="offTime">The off time.</param>
             <param name="velocity">The velocity.</param>
             <param name="acceleration">The acceleration.</param>
             <param name="decleration">The decleration.</param>
             <param name="timeout">The timeout.</param>
             <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.MotorRotateXdegrees(System.Byte,System.Byte,System.UInt16,System.Int16,System.UInt16,System.Int32)">
             <summary>
             The rotate X degrees command specifies the degrees of rotation, the target velocity, and the acceleration rate to use while rotating.
            If the Server does not implement the API221_DEVICE_ROTATE() macro, then the API221_CMD_ROTATE_X_DEGREES OpCode is not supported.
             </summary>
             <param name="target">The target.</param>
             <param name="motorId">The motor identifier.</param>
             <param name="degreesToRotate">The degrees to rotate.</param>
             <param name="velocity">The velocity.</param>
             <param name="acceleration">The acceleration.</param>
             <param name="timeout">The timeout.</param>
             <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.MotorPulseImmediate(System.Byte,System.Byte,System.UInt16,System.UInt16,System.Int16,System.UInt16,System.UInt16,System.Int32)">
            <summary>
            The pulse immediate command specifies the on time, the off time, the target velocity, the acceleration rate, and the deceleration rate to use for the pulse.
            If the Server does not implement the API221_DEVICE_PULSE() macro, then the API221_CMD_PULSE_IMMEDIATE OpCode is not supported.
            </summary>
            <param name="target">The target.</param>
            <param name="motorId">The motor identifier.</param>
            <param name="onTime">The on time.</param>
            <param name="offTime">The off time.</param>
            <param name="velocity">The velocity.</param>
            <param name="acceleration">The acceleration.</param>
            <param name="decleration">The decleration.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.MotorPulseModify(System.Byte,System.Byte,System.UInt16,System.UInt16,System.Int16,System.UInt16,System.UInt16,System.Int32)">
             <summary>
             The pulse modify command specifies the on time, the off time, the target velocity, the acceleration rate, and the deceleration rate to use for the pulse.
            If the Server does not implement the API221_DEVICE_PULSE() macro, then the API221_CMD_PULSE_MODIFY OpCode is not supported.
             </summary>
             <param name="target">The target.</param>
             <param name="motorId">The motor identifier.</param>
             <param name="onTime">The on time.</param>
             <param name="offTime">The off time.</param>
             <param name="velocity">The velocity.</param>
             <param name="acceleration">The acceleration.</param>
             <param name="decleration">The decleration.</param>
             <param name="timeout">The timeout.</param>
             <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.MotorPulseQueue(System.Byte,System.Byte,System.UInt16,System.UInt16,System.Int16,System.UInt16,System.UInt16,System.Int32)">
             <summary>
            The pulse queue command specifies the on time, the off time, the target velocity, the acceleration rate, and the deceleration rate to use for the pulse.
             If the Server does not implement the API221_DEVICE_PULSE() macro, then the API221_CMD_PULSE_QUEUE OpCode is not supported.
             </summary>
             <param name="target">The target.</param>
             <param name="motorId">The motor identifier.</param>
             <param name="onTime">The on time.</param>
             <param name="offTime">The off time.</param>
             <param name="velocity">The velocity.</param>
             <param name="acceleration">The acceleration.</param>
             <param name="decleration">The decleration.</param>
             <param name="timeout">The timeout.</param>
             <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.FixEndianess(System.Byte[],System.Boolean)">
            <summary>
            Fixes the endianess from BitConverter get bytes function.
            </summary>
            <param name="byteValue">The bytes value.</param>
            <param name="isLittleEndian">if set to <c>true</c> the output will be little endian.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetUpPeriodicAnalogData(System.Byte,System.UInt16,System.Byte,System.Boolean[])">
            <summary>
            Sets up periodic analog data.
             The API provides some limited data acquisition features for platformspecific analog data channels.The client can choose the analog data channels to monitor and the rate at which the motor controller should publish the analog data.
            API221 will use a single publication period for all the motors and their analog data values on the same motor controller.
            </summary>
            <param name="target">The target.</param>
            <param name="period">The period.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="analogChannelsBitmap">The analog channels bitmap.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishPeriodicAnalogdata(System.Byte,System.Byte,System.Boolean[],System.Int32)">
            <summary>
            Publishes 1 or more periodic Analog Data Values.
            Each value consists of 6 bytes:
            Byte 1: Motor Node and Motor Index
            Byte 2: Analog Channel
            Bytes 3-6:Analog Data Value
            </summary>
            <param name="target">The target.</param>
            <param name="motorIndex">Index of the motor.</param>
            <param name="analogChannelsBitmap">The analog channels bitmap.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetWifiDiagnosticMode(System.Byte,System.Boolean,System.Int32)">
            <summary>
            Sets the wifi diagnostic mode. Instruct ECM to start or stop factory diagnostic test mode 
            </summary>
            <param name="target">The target.</param>
            <param name="diag_mode">if set to <c>true</c> [diag mode].</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetFactoryDefault(System.Byte,System.Int32)">
            <summary>
            Sets the factory default.Instruct ECM to deprovision
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ResetAutoFactoryCounter(System.Byte,System.Int32)">
            <summary>
            Resets the automatic factory counter.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.DisableAutoFactory(System.Byte,System.Int32)">
            <summary>
            Disables the automatic factory.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetRegulatoryCode(System.Byte,System.Byte,System.Int32)">
            <summary>
            Sets the regulatory code.
            </summary>
            <param name="target">The target.</param>
            <param name="xx">The xx.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetAntennaPower(System.Byte,NTL.OpcodesResultData.AntennaPowerConfig,System.Int32)">
            <summary>
            Sets the antenna power.
            </summary>
            <param name="target">The target.</param>
            <param name="powerConfig">The power configuration.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetAntennaConfig(System.Byte,NTL.OpcodesResultData.AntennaConfig,System.Int32)">
            <summary>
            Sets the antenna configuration.
            </summary>
            <param name="target">The target.</param>
            <param name="antennaConfig">The antenna configuration.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.EraseConfiguration(System.Byte,System.Int32)">
            <summary>
            Erases the configuration.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ProvisionToWhirlpoolTest(System.Byte,System.Int32)">
            <summary>
            Provisions to whirlpool test.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetLinkStatus(System.Byte,System.Int32)">
            <summary>
            Gets the link status.Not valid for factory test on Gen3 and Gen4
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetUniqueID(System.Byte,System.Int32)">
            <summary>
            Gets the unique identifier.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAntennaRSSI(System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the antenna rssi.0 for ant A and 1 for ant B.RSSI value will be received after 7-15 sec
            </summary>
            <param name="target">The target.</param>
            <param name="antennaId">The antenna identifier.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRegulatoryCode(System.Byte,System.Int32)">
            <summary>
            Gets the regulatory code.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetCurrentTxPower(System.Byte,System.Int32)">
            <summary>
            Gets the current tx power.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetAntennaPowerConfiguration(System.Byte,System.Int32)">
            <summary>
            Gets the antenna power configuration.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetMACAddress(System.Byte,System.Int32)">
            <summary>
            Gets the mac address.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.FirmwareDownload(ProgramAgentLib.IPAEngineProgress,System.IO.Stream,System.Byte,System.UInt16,System.Boolean)">
            <summary>
            This method flashes firmware to the ACU. It requires that ACU is flashed with IAP/Bootloader already as this method
            supports only IAP version of firmware. Remember to configure CCB2 to WIN after the completion of download process.
            </summary>
            <param name="progress">The progress.</param>
            <param name="stream">It takes stream as input, cannot accept .s19 file path. Your application should use the firmware/.s19 file path and open it , send the stream reference to this method .</param>
            <param name="target">The target.</param>
            <param name="timerReset">The timer reset and default value is 1ms, can increase it as per your application requirement</param>
            <param name="partialImage">if set to <c>true</c> [partial image].</param>
            <returns>
            Task
            </returns>
            <example> The following example shows to call a firmware download function of NTL in C#
            <code source="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Firmware download example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.FirmwareDownloadViaHTTP(NTL.OpcodesResultData.IHttpFirmwareDownloadProgress,System.String,System.UInt32,System.Byte,NTL.OpcodesResultData.EraseTypes,System.UInt32,System.Int32,System.Int32)">
            <summary>
            Firmwares the download via HTTP.
            </summary>
            <param name="progress">The progress.</param>
            <param name="url">The URL.</param>
            <param name="crc32">The CRC32.</param>
            <param name="target">The target.</param>
            <param name="eraseType">Type of the erase.</param>
            <param name="startAddress">The start address.</param>
            <param name="payloadSize">Size of the payload.</param>
            <param name="statusTimeout">The status timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitFirmwareFlashProcess(NTL.OpcodesResultData.IHttpFirmwareDownloadProgress,System.Int32,System.String)">
            <summary>
            Waits the firmware flash process.
            </summary>
            <param name="progress">The progress.</param>
            <param name="statusTimeout">The status timeout.</param>
            <param name="command">The command. Set-Nodeupdate or Get-NodeUpdate</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ResumeFirmwareDownloadViaHTTP(NTL.OpcodesResultData.IHttpFirmwareDownloadProgress,System.Int32)">
            <summary>
            Resumes the firmware download via HTTP.
            </summary>
            <param name="progress">The progress.</param>
            <param name="statusTimeout">The status timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.Wait(System.Int32,System.Threading.CancellationToken)">
            <summary>
            Waits the specified miliseconds.
            </summary>
            <param name="miliseconds">The miliseconds.</param>
            <param name="token">The token.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.CancelFirmwareDownloadViaHTTP(System.Byte)">
            <summary>
            Cancels the firmware download via HTTP.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitStatus(System.Int32)">
            <summary>
            Waits the status.
            </summary>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitResult(System.Int32)">
            <summary>
            Waits the status.
            </summary>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SettingFileDownload(NTL.OpcodesResultData.ISettingFileProgress,System.IO.Stream,System.Byte,System.Boolean,System.Boolean)">
            <summary>
            This function downloads setting file to the board.
            </summary>
            <param name="progress">The progress.</param>
            <param name="stream">It takes stream as input, your application should use the setting file path and open it and send the stream reference to this method.</param>
            <param name="target">The target.</param>
            <param name="isBinary">if set to <c>true</c> the incoming stream is considered as binary.</param>
            <param name="waitForResetComplete">if set to <c>true</c> wait for reset complete before the Task finish.</param>
            <returns>
            Task
            </returns>
            <remarks>
            Sequence diagram: <br /><img src="../DownloadSettingsFile .png" />
            </remarks>
            <example> The following example shows to call a settingfile download function of NTL in C#
            <code source="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="Setting file download example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.SettingFileDownload(System.IO.Stream,System.Byte,System.Boolean,System.Boolean)">
            <summary>
            Settings the file download.
            </summary>
            <param name="stream">The stream.</param>
            <param name="target">The target.</param>
            <param name="isBinary">if set to <c>true</c> [is binary].</param>
            <param name="waitForResetComplete">if set to <c>true</c> [wait for reset complete].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StopSettingFileDownload(System.Byte)">
            <summary>
            Stops the setting file download process.
            </summary>
            <param name="target">The target.</param>
        </member>
        <member name="M:NTL.NucleusHandler.DownloadSettingFile(NTL.OpcodesResultData.ISettingFileProgress,System.IO.Stream,System.Byte,System.Boolean,System.Boolean)">
            <summary>
            Downloads the setting file.
            </summary>
            <param name="progress">The progress.</param>
            <param name="stream">The stream.</param>
            <param name="target">The target.</param>
            <param name="isBinary">if set to <c>true</c> [is binary].</param>
            <param name="waitForResetComplete">if set to <c>true</c> wait for reset complete before the Task finish.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.AcuWriteSettingFileTableData(NTL.OpcodesResultData.ISettingFileProgress,System.Byte,System.Int64,System.Boolean)">
            <summary>
            Acus the write setting file table data.
            </summary>
            <param name="progress">The progress.</param>
            <param name="target">The target.</param>
            <param name="elapsedTime">The elapsed time.</param>
            <param name="isBinary">if set to <c>true</c> [is binary].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.FromBitConverterToRevealBytes(System.Byte[])">
            <summary>
            Froms the bit converter to reveal bytes.
            </summary>
            <param name="bytes">The bytes.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.StartCycle(System.Byte,System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Starts the cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="compartment">The compartment.</param>
            <param name="cycleIndex">Index of the cycle. An index of 1 indicates the Off cycle. Index 2 indicates the first user defined cycle.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
            <example> The following example shows to use Start cycle function of NTL in C#
            <code source = "..\NucleusToolsLib.Examples\Window2.xaml.cs" lang="C#" title="C#" region="Start Cycle example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.StartCycleWithOptions(System.Byte,System.Byte,System.Byte,System.Byte[],System.Byte,System.Int32)">
            <summary>
            Starts the cycle with options.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="compartment">The compartment.</param>
            <param name="regulations">The regulations.</param>
            <param name="cycleIndex">Index of the cycle.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PauseCycle(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Stops the cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="compartment">The compartment.</param>
            <param name="cycleIndex">Index of the cycle.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
            <example> The following example shows to use Pausecycle function of NTL in C#
            <code source="..\NucleusToolsLib.Examples\Window2.xaml.cs" lang="C#" title="C#" region="Pause cycle example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.ResetCycle(System.Byte,System.Byte,System.Int32)">
            <summary>
            Resets the cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="compartment">The compartment.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.ResetCycle(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Resets the cycle.
            </summary>
            <param name="target">The target.</param>
            <param name="compartment">The compartment.</param>
            <param name="cycleIndex">Index of the cycle.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.LabelFileParser(System.IO.Stream)">
            <summary>
            This method requires NKM XML file
            Open the NKM file from your application and feed the stream output to the stream input of this function
            Provides information about Id, Name, Offset for loads, LLIs, GIs, Pilots, Regulations, Cycles and faults
            </summary>
            <param name="XMLstream">The xml stream.</param>
            <returns>
              <see cref="T:NTL.NKMParser.Configurations" />
            </returns>
            <example> The following example shows how to get id and other related info using a load Label"Drain Pump" in C#
            <code source="..\NucleusToolsLib.Examples\MainWindow.xaml.cs" lang="C#" title="C#" region="NKM file parser example" /></example>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToRegulations(System.Byte,System.Func{System.Byte[],System.Byte[]})">
            <summary>
            Publishes the regulation.
            </summary>
            <param name="target">The target.</param>
            <param name="regulations">The regulations.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToMessage(System.String,WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Responds to message.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMessage">The RCD MSG.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishRegulations(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Publishes the regulations.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="regulationArray">The regulation array.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.SetStatus(System.Byte,System.Byte,System.Byte[])">
            <summary>
            Sets the status.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="statusVariables">The status variables.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToRequestStatus(System.String,WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Responds to set status.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMessage">The received message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishStatus(System.Byte,System.Byte,System.Byte[],System.Int32)">
            <summary>
            Publishes the status.
            </summary>
            <param name="target">The target.</param>
            <param name="productType">Type of the product.</param>
            <param name="statusVariables">The status variables.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitRequestSettingsFileSectionID(System.Byte,System.UInt16,System.UInt16,NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Waits the settings file section identifier request.
            </summary>
            <param name="sectionId">The section identifier.</param>
            <param name="crc">The CRC.</param>
            <param name="size">The size.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToRequestSettingsFileSectionID(System.String,WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Responds to request settings file section identifier.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMessage">The received message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRespondToRequestSettingsFileSectionID(WhirlpoolCommunication.Packets.RevealPacket,System.UInt16,System.UInt16)">
            <summary>
            Responds to request settings file section identifier.
            </summary>
            <param name="receivedMessage">The received message.</param>
            <param name="sfSectionCrc">The sf section CRC.</param>
            <param name="sfSectionSize">Size of the sf section.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitRequestSettingsFileSectionData(System.Byte[],NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Waits the request settings file section data.
            </summary>
            <param name="secData">The sec data.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToRequestSettingsFileSectionData(WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Responds to request settings file section data.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMessage">The received message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitRequestMaxPackageSize(System.Byte,System.Byte,System.Byte,NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Waits the size of the request maximum package.
            </summary>
            <param name="target">The target.</param>
            <param name="maxSendSize">Maximum size of the send.</param>
            <param name="maxReceiveSize">Maximum size of the receive.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.RespondToWaitRequestMaxPackageSize(System.String,WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Responds the size of to wait request maximum package.
            </summary>
            <param name="id">The identifier.</param>
            <param name="receivedMessage">The received message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRequestMaxPackageSize(WhirlpoolCommunication.Packets.RevealPacket,System.Byte,System.Byte)">
            <summary>
            Gets the size of the request maximum package.
            </summary>
            <param name="receivedMessage">The received message.</param>
            <param name="maxSendSize">Maximum size of the send.</param>
            <param name="maxReceiveSize">Maximum size of the receive.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishSettingFileInfoByID(System.Byte,System.UInt16,System.UInt16)">
            <summary>
            Publishes the hmi setting file information.
            </summary>
            <param name="sectionId">The section identifier.</param>
            <param name="crc">The CRC.</param>
            <param name="size">The size.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.PublishSettingFileInfo(System.UInt16,System.UInt32,System.UInt16,System.UInt32,System.UInt32,System.UInt32)">
            <summary>
            Publishes the setting file information.
            </summary>
            <param name="acuCrc">The acu CRC.</param>
            <param name="acuSize">Size of the acu.</param>
            <param name="hmiCrc">The hmi CRC.</param>
            <param name="hmiSize">Size of the hmi.</param>
            <param name="sfSize">Size of the sf.</param>
            <param name="sfAddress">The sf address.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitRequestSegmentInfo(System.Byte,NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Waits the request settings file segment.
            </summary>
            <param name="segmentId">The segment identifier.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.GetRequestSegmentInfo(WhirlpoolCommunication.Packets.RevealPacket)">
            <summary>
            Gets the request segment information.
            </summary>
            <param name="receivedMessage">The received message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.WaitRequestSegmentData(System.Byte,NTL.Reveal.RequestDataResult,System.Int32)">
            <summary>
            Waits the request segment data.
            </summary>
            <param name="segmentId">The segment identifier.</param>
            <param name="requestDataResult">The request data result.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.UploadSettingFile(NTL.OpcodesResultData.ISettingFileProgress,System.Byte,System.Byte,System.UInt16,System.UInt16,System.Byte[],System.Int32)">
            <summary>
            Uploads the setting file. Set the CCB2 address as 1 to emulate ACU for SF uploading.
            </summary>
            <param name="progress">The progress.</param>
            <param name="requesterNode">The requester node, eg:HMI node.</param>
            <param name="sectionId">The section identifier.</param>
            <param name="crc">The CRC.</param>
            <param name="size">The size.</param>
            <param name="sfData">The sf data.</param>
            <param name="timeout">The timeout, set it to minimum of 5000mSecs.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.Delay(System.Int32)">
            <summary>
            Delays the specified miliseconds delay.
            </summary>
            <param name="milisecondsDelay">The miliseconds delay.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.NucleusHandler.Dispose">
            <summary>
            Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
            </summary>
        </member>
        <member name="M:NTL.NucleusHandler.GetAndSetCalibrationData(System.Byte,System.Byte,System.Byte,System.Int32)">
            <summary>
            Gets the and set calibration data.
            </summary>
            <param name="target">The target.</param>
            <param name="calibrationId">The calibration Id </param>
            <param name="memoryMappedVariableId">The memory mapped variable Id is the Id used to assign an Id for DefineMemoryMappedVariable method.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.API_NUMBER">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.NOAPI">
            <summary>
            NO APIs
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API001">
            <summary>
            api001: Core
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API002">
            <summary>
            api002:
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API003">
            <summary>
            api003: Discovery
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API004">
            <summary>
            api004: Debug
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API005">
            <summary>
            api005: Low Level
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API007">
            <summary>
            api007: Data
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API009">
            <summary>
            api009: System
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API010">
            <summary>
            api010: Poll Var
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API011">
            <summary>
            api011: Application Control
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API012">
            <summary>
            api012: Expansion Board
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API017">
            <summary>
            The ap i017
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API018">
            <summary>
            api018: Diagnostic
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API019">
            <summary>
            api019: Product Info
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API020">
            <summary>
            The api020: Safety
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API220">
            <summary>
            The ap i220: Motor FVT
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API221">
            <summary>
            The API221: Motion control
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API141">
            <summary>
            The ap i141
            </summary>
        </member>
        <member name="F:NTL.API_NUMBER.API_MAX">
            <summary>
            The api maximum
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API001">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_ACK">
            <summary>
            Publish ack
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_HEARTBEAT">
            <summary>
            Publish heartbeat
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.SET_HEARTBEAT">
            <summary>
            Set heartbeat
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_MEM">
            <summary>
            Publish memory
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.READ_MEM_24B">
            <summary>
            Read memory 24 b
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.READ_EE">
            <summary>
            Read ee
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.SEND_EVENTS">
            <summary>
            Send events
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_EE">
            <summary>
            Publish ee
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.READ_MEM_32B">
            <summary>
            Read memory 32 b
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_HEARTBEAT_PERIOD">
            <summary>
            Publish heartbeat period
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.MAX_MESSAGE_SIZE">
            <summary>
            Max message size
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_WAKEUP">
            <summary>
            Publish wakeup
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API001.PUBLISH_ACK_WAKEUP">
            <summary>
            Publish ack wakeup
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API220">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API220.MCI_ERROR_COMMAND">
            <summary>
            Get MCI error results
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API220.FVT_COMMAND">
            <summary>
            The FVT command
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API221">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.FAILURE_FLAGS">
            <summary>
            The publish reveal flags
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.KEEP_RUNNING">
            <summary>
            The keep running
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PUBLISH_EVENT">
            <summary>
            The publish event
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.MOTION_BEHAVIOR">
            <summary>
            The set motion behavior
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.MOTOR_STATUS">
            <summary>
            The publish motor status
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.ANALOG_DATA">
            <summary>
            The publish analog data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.DATA_PUBLICATION_PERIOD">
            <summary>
            The data publication period
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PERIODIC_DATA">
            <summary>
            The periodic data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.ADD_ANALOG_CHANNELS_BITMAP">
            <summary>
            The analog channels bitmap
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.REMOVE_ANALOG_CHANNELS_BITMAP">
            <summary>
            The remove analog channels bitmap
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PERIODIC_DATA_STATUS">
            <summary>
            The publish periodic data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.WASH">
            <summary>
            The wash
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.ROTATE_X_DEGREES">
            <summary>
            The rotate x degrees
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PULSE_IMMEDIATE">
            <summary>
            The pulse immediate
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PULSE_MODIFY">
            <summary>
            The pulse modify
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.PULSE_QUEUE">
            <summary>
            The pulse queue
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.CLEAR_FAILURE_FLAGS">
            <summary>
            The clear failure flags
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.STOP">
            <summary>
            The stop
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API221.RUN">
            <summary>
            The run
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API003">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.FIND_REVEAL_NODES">
            <summary>
            Find reveal nodes
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.PUBLISH_REVEAL_NODES">
            <summary>
            Publish reveal nodes
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.GET_REVEAL_APIS">
            <summary>
            Get reveal apis
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.PUBLISH_REVEAL_APIS">
            <summary>
            Publish reveal apis
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.GET_API_INFO">
            <summary>
            Get api info
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.PUBLISH_API_INFO">
            <summary>
            Publish api info
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.GET_INSTANCE_INFO">
            <summary>
            Get instance info
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API003.PUBLISH_INSTANCE_INFO">
            <summary>
            Publish instance info
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API005">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.SET_LOAD">
            <summary>
            Set load
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_LOAD_DATA">
            <summary>
            Get and publish load data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_LLI_DATA">
            <summary>
            Get and publish Low Level Input Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_GI_CONVERTED_DATA">
            <summary>
            Get and publish Generic Input converted data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_ALL_LOAD_CONFIGURATION">
            <summary>
            Get and publish all load configuration
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_ALL_LLI_CONFIGURATION">
            <summary>
            Get and publish all LLI configuration
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.GET_PUB_ALL_GI_CONFIGURATION">
            <summary>
            Get and publish all GI configuration
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.PUB_EVENT">
            <summary>
            Publish event
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.CALL_DEBUG_FUNCTION">
            <summary>
            Call debug function
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.DEBUG_LABEL">
            <summary>
            Debug label
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.SET_DEBUG_VARIABLE">
            <summary>
            Set debug variable
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_SET_OBJECT">
            <summary>
            HMI set object
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_PLAY_SOUND">
            <summary>
            HMI play sound
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_PUB_GI">
            <summary>
            HMI PUBLISH GI
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_PUB_LLI">
            <summary>
            HMI PUBLISH LLI
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_PUB_GI_CONFIG">
            <summary>
            HMI PUBLISH GI CONFIG
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.HMI_PUB_LLI_CONFIG">
            <summary>
            HMI PUBLISH LLI CONFIG
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.SET_TEST_STORAGE">
            <summary>
            Set test storage
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.ENGAGE_TEST_CYCLE">
            <summary>
            Engage test cycle
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.PHASE_TEST_CYCLE">
            <summary>
            Phase test cycle
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.EXTRACT_LOADS">
            <summary>
            Extract loads
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.EXTRACT_GIS">
            <summary>
            Extract gis
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API005.JUMP_STEP">
            <summary>
            The jump step
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API007">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.MEM_WRITE_RAM_24BIT">
            <summary>
            Write RAM 24 bit
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.MEM_WRITE_RAM_32BIT">
            <summary>
            Write RAM 32 bit
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_SEGMENT_INFO">
            <summary>
            The req segment information
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_SEGMENT_ALL_DATA">
            <summary>
            The req segment data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTING_FILE_INFO">
            <summary>
            Request and publish setting file information
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_HMI_SETTING_FILE_DATA">
            <summary>
            Request and publish setting file data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTING_FILE_TABLE_SIZE">
            <summary>
            Request and publish setting file table size
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTING_FILE_TABLE">
            <summary>
            Request and publish setting file table
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.ERASE_FLASH">
            <summary>
            Erase flash
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.WRITE_FLASH">
            <summary>
            Write flash
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.FLASH_PROCESS_DONE">
            <summary>
            Flash process done
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_FLASH_ALIGNMENT">
            <summary>
            Request and publish flash alignment
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTINGS_FILE_INFO_BY_ID">
            <summary>
            Request and publish setting file id info
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTINGS_FILE_DATA_BY_ID">
            <summary>
            Request and publish setting file id data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTINGS_FILE_DISPLACEMENT_INFO">
            <summary>
            Request and publish setting file displacement info
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.REQ_PUB_SETTINGS_FILE_DISPLACEMENT_DATA">
            <summary>
            Request and publish setting file displacement data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.DEBUG">
            <summary>
            Debug
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API007.ERROR">
            <summary>
            Error
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API009">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API009.FORCE_RESET">
            <summary>
            The forc e_ reset
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API009.REQUEST_LOW_POWER_MODE">
            <summary>
            The request low power mode
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API009.REQUEST_WHO_WAKE_SYSTEM">
            <summary>
            The request who wake system
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API010">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.REQUEST_SPECIFIC_VARIABLE">
            <summary>
            Read specific
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.PUBLISH_SPECIFIC_VARIABLE">
            <summary>
            Publish one data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.ENABLE_PERIODIC_DATA">
            <summary>
            Set extraction engine state
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.PUBLISH_STREAM_DATA">
            <summary>
            publish stream
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.DESELECT_ALL_VARIABLES">
            <summary>
            Disable all extractions
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.SELECT_ALL_VARIABLES">
            <summary>
            Enable all extractions
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.DESELECT_SPECIFIC_VARIABLES">
            <summary>
            Disable specific extraction
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.SELECT_SPECIFIC_VARIABLES">
            <summary>
            Enable specific extraction
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.SETUP_PERIODIC_PUBLICATION">
            <summary>
            Set extraction engine state
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.DEFINE_MEMORY_MAPPED_VARIABLE">
            <summary>
            Set dynamic vars
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.UNDEFINE_MEMORY_MAPPED_VARIABLE">
            <summary>
            Clear dynamic vars
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.CONFIGURE_ONCHANGE_BEHAVIOR">
            <summary>
            Set on change
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.REQUEST_FIXED_VARIABLE_METADATA">
            <summary>
            Request system index config
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.PUBLISH_FIXED_VARIABLE_METADATA">
            <summary>
            Publish system index config
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.REQUEST_ACQUISITION_CONFIGURATION">
            <summary>
            The request acquisition configuration
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.PUBLISH_ACQUISITION_CONFIGURATION">
            <summary>
            The publish acquisition configuration
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.REQUEST_NUMBER_OF_VARIABLES">
            <summary>
            The request number of variables
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.PUBLISH_NUMBER_OF_VARIABLES">
            <summary>
            The publish number of variables
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API010.WRITE_FIXED_VARIABLE">
            <summary>
            The write fixed variable
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API011">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REQ_PUB_IDENT_TABLE">
            <summary>
            Request and publish ident table (obsolete)
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REQ_PUB_IDENT_TABLE16B">
            <summary>
            Request and publish ident table 16 b (obsolete)
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REQ_PUB_STATUS">
            <summary>
            Request and publish status
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REQ_PUB_REGULATIONS">
            <summary>
            Request and publish regulations
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.SET_REGULATIONS">
            <summary>
            Set Regulations
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REQ_PUB_MODE">
            <summary>
            Request and publish system mode
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.SET_MODE">
            <summary>
            Set system mode
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.MODE_HEARTBEAT">
            <summary>
            Mode Hearbeat
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REG_POSITION_BY_ID">
            <summary>
            Request and publish regulation by id
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REG_NUM_CYCLES">
            <summary>
            Request and publish number of cycles
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REG_PUB_STATUS_STRUCTURE">
            <summary>
            Request and publish status structure
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REG_PUB_FUNCTIONS_ID">
            <summary>
            Request and publish functions id
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API011.REG_PUB_CYCLE_NAMES">
            <summary>
            The reg pub cycle names
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API012">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.REQ_PUB_LOAD_INFO">
            <summary>
            Request and publish load information
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.REQ_PUB_GI_INFO">
            <summary>
            Request and publish GI information
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.REQ_PUB_LOADS">
            <summary>
            Request and publish loads
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.SET_LOADS">
            <summary>
            Set loads
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.REQ_PUB_GIS">
            <summary>
            Request and publish gis
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.SET_VIEW_ELEMENTS">
            <summary>
            Set view elements
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.PUBLISH_KEY_STATUS">
            <summary>
            Publish key status
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.PLAY_SOUND">
            <summary>
            Play sound
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.SET_VOLUME">
            <summary>
            Set volume
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API012.STOP_SOUND">
            <summary>
            Stop sound
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API017">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API017.REQUEST_TOUCH_DATA">
            <summary>
            The request touch data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API017.PUB_TOUCH_DATA">
            <summary>
            The publish touch data
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API018">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API018.GENERATE_FAULT">
            <summary>
            Save fault
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API018.CLEAR_SAVED_FAULT">
            <summary>
            Clear saved fault
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API018.REQ_PUB_SAVED_FAULT_CODE">
            <summary>
            Request and publish saved fault code
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API018.REQ_PUB_STATISTICS">
            <summary>
            Request and publish statistics
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API018.REB_PUB_DIAGNOSTIC_CONFIG">
            <summary>
            Request and publish diagnostic configuration
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API019">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_APPLIANCE_DATA">
            <summary>
            Request and Publish Appliance Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_APPLIANCE_DATA">
            <summary>
            Set Appliance Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_BOARD_DATA">
            <summary>
            Request and Publish Board Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_BOARD_DATA">
            <summary>
            Set Board Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_PROJECT_DATA">
            <summary>
            Request and publish project
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_SERVICE_DATA">
            <summary>
            Request and publish service data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_SERVICE_DATA">
            <summary>
            Set Service Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_FVT_DATA">
            <summary>
            Request and publish fvt data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_FVT_DATA">
            <summary>
            Set fvt Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_FVT_DATA_BYTES_RESULT">
            <summary>
            Set fvt Data bytes result
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_PUB_EOL_DATA">
            <summary>
            Request and publish eol data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_EOL_DATA">
            <summary>
            Set eol Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_EOL_DATA_BYTES_RESULT">
            <summary>
            Set eol Data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.STORE_STATIC_DATA">
            <summary>
            Store static data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_CALIBRATION_DATA">
            <summary>
            The req calibration data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.SET_CALIBRATION_DATA">
            <summary>
            The set calibration data
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API019.REQ_CLASSB_SIGNATURE_DATA">
            <summary>
            The req classb signature data
            </summary>
        </member>
        <member name="T:NTL.OPCODES_API141">
            <summary>
            
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.SET_DIAGNOSTIC_MODE">
            <summary>
            The set diagnostic mode
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.GET_LINK_STATUS">
            <summary>
            The get link status
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.GET_UNIQUE_ID">
            <summary>
            The get unique identifier
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.SET_FACTORY_DEFAULT">
            <summary>
            The set factory default
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.GET_ANTENNA_RSSI">
            <summary>
            The get antenna rssi
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.OPERATION_COMMAND">
            <summary>
            The operation command
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.RADIO_COMMAND">
            <summary>
            The radio command
            </summary>
        </member>
        <member name="F:NTL.OPCODES_API141.MAC_ADDRESS">
            <summary>
            The mac address
            </summary>
        </member>
        <member name="T:NTL.SFDownloadState">
            <summary>
            Setting file download state enumerations
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.IDLE">
            <summary>
            The idle
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.STARTING">
            <summary>
            start the process
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.LOAD_FILE">
            <summary>
            The load file
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.REQUEST_REVEAL_MSG_SIZE">
            <summary>
            The request reveal msg size
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.REQUEST_SF_INFOR">
            <summary>
            The request sf information
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.SET_MODE">
            <summary>
            The set mode
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.REQUEST_FLASH_ALIGNMENT">
            <summary>
            The request flash alignment
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.ERASE_FLASH">
            <summary>
            The erase flash
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.WRITE_DATA">
            <summary>
            The write data
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.WRITE_DATA_COMPLETE">
            <summary>
            The write data is Completed
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.DOWNLOAD_COMPLETE">
            <summary>
            The end process
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.DOWNLOAD_CANCELED">
            <summary>
            The cancel download
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.DOWNLOAD_ERROR">
            <summary>
            Process Stopped for error
            </summary>
        </member>
        <member name="F:NTL.SFDownloadState.END_PROCESS">
            <summary>
            The end process
            </summary>
        </member>
        <member name="T:NTL.SettingFileHelper">
            <summary>
            
            
            </summary>
        </member>
        <member name="M:NTL.SettingFileHelper.ConvertLongToArray(System.UInt32)">
            <summary>
            Converts the long to array.
            </summary>
            <param name="data">The data.</param>
            <returns>
            Byte Array
            </returns>
        </member>
        <member name="M:NTL.SettingFileHelper.ConvertIntToArray(System.Int32)">
            <summary>
            Converts the int to array.
            </summary>
            <param name="data">The data.</param>
            <returns>
            Byte Array
            </returns>
        </member>
        <member name="M:NTL.SettingFileHelper.ConvertArrayToLong(System.Collections.Generic.List{System.Byte},System.Int32)">
            <summary>
            Convert a byte array into a long
            </summary>
            <param name="all_payload">The all_payload.</param>
            <param name="startIndex">The start index.</param>
            <returns>
            UInt32
            </returns>
        </member>
        <member name="M:NTL.SettingFileHelper.ConvertToUint(System.Byte,System.Byte)">
            <summary>
            Converts 2 bytes to uint.
            </summary>
            <param name="MSB">The MSB.</param>
            <param name="LSB">The LSB.</param>
            <returns>
            unsigned integer
            </returns>
        </member>
        <member name="M:NTL.UnitConverter.ConvertIntToArray(System.Int32)">
            <summary>
            Converts the int to array.
            </summary>
            <param name="data">The data.</param>
            <returns>Byte Array</returns>
        </member>
        <member name="M:NTL.UnitConverter.ConvertArrayToLong(System.Collections.Generic.List{System.Byte},System.Int32)">
            <summary>
            Convert a byte array into a long
            </summary>
            <param name="all_payload">The all_payload.</param>
            <param name="startIndex">The start index.</param>
            <returns>UInt32</returns>
        </member>
        <member name="M:NTL.UnitConverter.ConvertToUint(System.Byte,System.Byte)">
            <summary>
            Converts 2 bytes to uint.
            </summary>
            <param name="MSB">The MSB.</param>
            <param name="LSB">The LSB.</param>
            <returns>unsigned integer</returns>
        </member>
        <member name="T:NTL.VariableHandler">
            <summary>
            Handle variables!
            </summary>
            <seealso cref="T:WhirlpoolCommunication.IMessageHandler" />
        </member>
        <member name="F:NTL.VariableHandler.nucleusHandler">
            <summary>
            The nucleus handler.
            </summary>
        </member>
        <member name="F:NTL.VariableHandler.revealHandler">
            <summary>
            The reveal handler.
            </summary>
        </member>
        <member name="F:NTL.VariableHandler.isPeriodicDataEnabled">
            <summary>
            The is periodic data enabled
            </summary>
        </member>
        <member name="F:NTL.VariableHandler.periodicDataCancellationToken">
            <summary>
            The periodic data cancellation token
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.NKMHandler">
            <summary>
            Gets or sets the NMK handler.
            </summary>
            <value>
            The NMK handler.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.DeviceAddress">
            <summary>
            Gets or sets the device address.
            To disable auto responses put Device Address equals to 255 (0xFF).
            </summary>
            <value>
            The device address.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.IsPeriodicDataEnabled">
            <summary>
            Gets or sets a value indicating whether this instance the periodic data enabled for publishing Device Variables.
            </summary>
            <value>
              <c>true</c> if this instance is periodic data enabled; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.PublicationPeriod">
            <summary>
            Gets or sets the publication period for publishing Device Variables.
            </summary>
            <value>
            The publication period.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.ProductType">
            <summary>
            Gets or sets the type of the product.
            </summary>
            <value>
            The type of the product.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.StatusVariables">
            <summary>
            Gets the status variables.
            </summary>
            <value>
            The status variables.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.DeviceVariables">
            <summary>
            Gets the simulated variables.
            </summary>
            <value>
            The simulated variables.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.MachineVariables">
            <summary>
            Gets the machine variables.
            </summary>
            <value>
            The machine variables.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.Regulations">
            <summary>
            Gets the regulations.
            </summary>
            <value>
            The regulations.
            </value>
        </member>
        <member name="M:NTL.VariableHandler.VariableDataSize(System.Byte,System.Byte)">
            <summary>
            Variables the size of the data.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <returns></returns>
            <exception cref="T:System.Exception">
            </exception>
        </member>
        <member name="M:NTL.VariableHandler.SetMachineVariableFromStream(System.Byte,System.Byte[])">
            <summary>
            Sets the machine variable.
            </summary>
            <param name="source">The target.</param>
            <param name="streamData">The stream data.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SetMachineVariable(System.Byte,System.Byte,System.Byte[])">
            <summary>
            Sets the device variable.
            </summary>
            <param name="source">The source.</param>
            <param name="index">The index.</param>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SelectMachineVariables(System.Byte,System.Int32)">
            <summary>
            Selects the machine variables from the board.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SelectMachineVariables(System.Byte,System.Byte[])">
            <summary>
            Selects the machine variables given the variable id list.
            </summary>
            <param name="target">The target.</param>
            <param name="variableIds">The variable ids.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.AddMachineVariable(NTL.OpcodesResultData.VariableInfo,System.Byte,System.Boolean,System.Int32)">
            <summary>
            Adds a machine variable.
            </summary>
            <param name="varInfo">The variable information.</param>
            <param name="source">The source.</param>
            <param name="overrideId">if set to <c>true</c> [override identifier].</param>
            <param name="arrayMultiple">The array multiple. If set a value bigger than 1, it will create new VariableInfo adding to the offset 
            and if the VariableInfo have memory address it will add to the value times the byte size of the VarType.
            The name also will get appended with the index VarName_i.
            </param>
            <exception cref="T:System.ArgumentException"></exception>
            <exception cref="T:System.ArgumentException"></exception>
        </member>
        <member name="M:NTL.VariableHandler.GetSelectedMachineVariablesIndexes(System.Byte)">
            <summary>
            Gets the index array of the selected machine variables with given source (target). 
            Variables where IsSelected is true.
            </summary>
            <param name="target">The target.</param>
            <returns>Return the index list of the selected variables</returns>
        </member>
        <member name="M:NTL.VariableHandler.GetSelectedMachineVariables(System.Byte)">
            <summary>
            Gets the selected machine variables.
            </summary>
            <param name="target">The target.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SetSelectedMachineVariables(System.Byte,System.Byte,System.Boolean)">
            <summary>
            Sets the selected machine variables based on the index.
            Returns the number of variables set.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="isSelected">if set to <c>true</c> [is selected].</param>
        </member>
        <member name="M:NTL.VariableHandler.SetSelectedMachineVariables(System.Byte,System.Byte,System.Byte,System.Boolean)">
            <summary>
            Sets the selected machine variables based on the index and offset.
            Returns the number of variables set.
            </summary>
            <param name="target">The target.</param>
            <param name="index">The index.</param>
            <param name="offset">The offset.</param>
            <param name="isSelected">if set to <c>true</c> [is selected].</param>
        </member>
        <member name="M:NTL.VariableHandler.SetSelectedMachineVariables(System.Byte,System.String,System.Boolean)">
            <summary>
            Sets the selected machine variables based on the name.
            Returns the number of variables set.
            </summary>
            <param name="target">The target.</param>
            <param name="name">The machine variable name name.</param>
            <param name="isSelected">if set to <c>true</c> [is selected].</param>
        </member>
        <member name="M:NTL.VariableHandler.SelectSpecificMachineVariables(System.Byte,System.Int32)">
            <summary>
            Set to publication the specific selected machine variables.
            </summary>
            <param name="target">The target.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.ConfigureSelectedMemoryMappedVariables(System.Byte,System.Boolean,System.Int32)">
            <summary>
            Configures the selected memory mapped variables.
            </summary>
            <param name="target">The target.</param>
            <param name="enable">Set to <c>true</c> to define and <c>false </c> to undefine.</param>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.FixMemoryMappedIndexes(System.Byte,NTL.OpcodesResultData.NumberOfVariables)">
            <summary>
            Fixes the memory mapped indexes.
            </summary>
            <param name="target">The target.</param>
            <param name="numOfVars">The number of vars.</param>
        </member>
        <member name="M:NTL.VariableHandler.AddDeviceVariable(NTL.OpcodesResultData.VariableInfo,System.Boolean)">
            <summary>
            Adds a device variable.
            </summary>
            <param name="varInfo">The variable information.</param>
            <param name="overrideId">if set to <c>true</c> [override identifier].</param>
            <exception cref="T:System.ArgumentException"></exception>
        </member>
        <member name="M:NTL.VariableHandler.SetDeviceVariable(System.Byte,System.Byte,System.Object)">
            <summary>
            Sets the device variable.
            </summary>
            <param name="index">The index.</param>
            <param name="offset">The offset.</param>
            <param name="value">The value.</param>
        </member>
        <member name="M:NTL.VariableHandler.SetDeviceVariable(System.Byte,System.Object[])">
            <summary>
            Sets the device variable.
            </summary>
            <param name="index">The index.</param>
            <param name="value">The value.</param>
        </member>
        <member name="M:NTL.VariableHandler.SelectDeviceVariable(System.Byte,System.Boolean)">
            <summary>
            Selects the device variable.
            </summary>
            <param name="index">The index.</param>
            <param name="select">if set to <c>true</c> [select].</param>
            <returns>Return false if does not find any variable with the index</returns>
        </member>
        <member name="M:NTL.VariableHandler.SelectAllDeviceVariables(System.Boolean)">
            <summary>
            Selects all device variables.
            </summary>
            <param name="select">if set to <c>true</c> [select].</param>
        </member>
        <member name="M:NTL.VariableHandler.PublishDeviceVariables(System.Byte,System.UInt16)">
            <summary>
            Publishes the device variables.
            </summary>
            <param name="packageCount">The package count.</param>
            <param name="maxPackageSize">Maximum size of the package.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.PublishDeviceVariablesMetadata(System.Byte,System.UInt16)">
            <summary>
            Publishes the device variables metadata.
            </summary>
            <param name="variableId">The variable identifier.</param>
            <param name="maxPackageSize">Maximum size of the package.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.CheckDeviceVariable(System.Byte)">
            <summary>
            Checks if any device variable contains the given variable id.
            Always returns true if variableId equals to 255.
            </summary>
            <param name="variableId">The variable identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SelectRegulations(System.Collections.Generic.List{System.Byte[]})">
            <summary>
            Selects the status variables.
            </summary>
            <param name="regulationsDisplacements">The regulations displacements.</param>
        </member>
        <member name="M:NTL.VariableHandler.SelectRegulations(System.Byte[])">
            <summary>
            Selects the regulations based on an array of target and regulation.
            </summary>
            <param name="targetAndRegulations">The target and regulations array.</param>
        </member>
        <member name="M:NTL.VariableHandler.PublishRegulations">
            <summary>
            Publishes the regulations.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SetRegulation(System.Byte,System.Byte)">
            <summary>
            Sets the regulation.
            </summary>
            <param name="id">The identifier of the regulation.</param>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SetRegulation(System.String,System.Byte)">
            <summary>
            Sets the regulation.
            </summary>
            <param name="name">The name of the regulation.</param>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.#ctor(NTL.NucleusHandler,NTL.Reveal.RevealHandler,System.IO.Stream)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.VariableHandler" /> class.
            </summary>
            <param name="nucleusHandler">The nucleus handler.</param>
            <param name="revealHandler">The reveal handler.</param>
            <param name="XMLStream">The XML stream with the file for NKM Handler.</param>
        </member>
        <member name="M:NTL.VariableHandler.#ctor(NTL.NucleusHandler,NTL.Reveal.RevealHandler)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.VariableHandler"/> class.
            </summary>
        </member>
        <member name="M:NTL.VariableHandler.PublishStatusVariables">
            <summary>
            Publishes in broadcast the status variables.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.SelectStatusVariables(System.Byte[])">
            <summary>
            Selects the status variables.
            Status displacement is an array of index and offset of variables.
            </summary>
            <param name="statusDisplacement">The status displacement.</param>
            <exception cref="T:System.Exception">NKMHandler does not have configurations set.</exception>
        </member>
        <member name="M:NTL.VariableHandler.SetStatusVariable(System.Byte,System.Byte,System.Object)">
            <summary>
            Sets the status variable.
            Return true if find the Status with given index and offset.
            </summary>
            <param name="index">The index.</param>
            <param name="offset">The offset.</param>
            <param name="value">The value.</param>
        </member>
        <member name="M:NTL.VariableHandler.SetStatusVariable(System.String,System.Object)">
            <summary>
            Sets the status variable.
            Return true if find the Status with given name.
            </summary>
            <param name="name">The name.</param>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.ToByteArray(NTL.VariableHandler.VariableData[],System.Boolean)">
            <summary>
            To the byte array.
            </summary>
            <param name="varDataList">The variable data list.</param>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.Flatten(System.Byte[][])">
            <summary>
            Flattens the specified byte array.
            </summary>
            <param name="byteArray">The byte array.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.ParseMessage(WhirlpoolCommunication.Packets.IMessage)">
            <summary>
            Parses the message.
            </summary>
            <param name="message">The message.</param>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="M:NTL.VariableHandler.Dispose">
            <summary>
            Releases unmanaged and - optionally - managed resources.
            </summary>
        </member>
        <member name="T:NTL.VariableHandler.RegulationData">
            <summary>
            Class that represent a Regulation.
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.Name">
            <summary>
            Gets or sets the name.
            </summary>
            <value>
            The name.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.Id">
            <summary>
            Gets or sets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.Compartment">
            <summary>
            Gets or sets the compartment.
            </summary>
            <value>
            The compartment.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.Frozen">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.VariableHandler.RegulationData"/> is frozen.
            </summary>
            <value>
              <c>true</c> if frozen; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.Value">
            <summary>
            Sets the value.
            It will set client value and only if not Frozen also the Implementer Value.
            </summary>
            <value>
            The value.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.ImplementerValue">
            <summary>
            Gets or sets the implementer value.
            </summary>
            <value>
            The implementer value.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.ClientValue">
            <summary>
            Gets or sets the client value.
            </summary>
            <value>
            The client value.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.ClientValueAge">
            <summary>
            Gets the client value age.
            </summary>
            <value>
            The client value age.
            </value>
        </member>
        <member name="P:NTL.VariableHandler.RegulationData.ImplementerValueAge">
            <summary>
            Gets the implementer value age.
            </summary>
            <value>
            The implementer value age.
            </value>
        </member>
        <member name="E:NTL.VariableHandler.RegulationData.PropertyChanged">
            <summary>
            Occurs when a property value changes.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.RegulationData.OnPropertyChanged(System.String)">
            <summary>
            Called when property changed.
            </summary>
            <param name="propertyName">Name of the property.</param>
        </member>
        <member name="T:NTL.VariableHandler.VariableData">
            <summary>
            Variable Data class that can be used to track or mimic a machine variable.
            </summary>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.source">
            <summary>
            The source
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.VariableData.Source">
            <summary>
            Gets or sets the source.
            </summary>
            <value>
            The source.
            </value>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.isSelected">
            <summary>
            The is selected
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.VariableData.IsSelected">
            <summary>
            Gets or sets a value indicating whether this instance is selected.
            </summary>
            <value>
              <c>true</c> if this instance is selected; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.valueAge">
            <summary>
            The value age
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.VariableData.ValueAge">
            <summary>
            Gets or sets the value age.
            </summary>
            <value>
            The value age.
            </value>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.varInfo">
            <summary>
            The variable information
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.VariableData.VariableInfo">
            <summary>
            Gets or sets the variable information.
            </summary>
            <value>
            The variable information.
            </value>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.value">
            <summary>
            The value
            </summary>
        </member>
        <member name="P:NTL.VariableHandler.VariableData.Value">
            <summary>
            Gets or sets the value.
            </summary>
            <value>
            The value.
            </value>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.InitializeValue">
            <summary>
            Initializes the value with default value of its variable info type.
            </summary>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToByteArray(System.Boolean)">
            <summary>
            To the byte array.
            </summary>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.GetBytes(System.Object)">
            <summary>
            Gets the bytes.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.FixEndianess(System.Byte[],System.Boolean)">
            <summary>
            Fixes the endianess.
            </summary>
            <param name="bytes">The bytes.</param>
            <param name="isLittleEndian">if set to <c>true</c> [is little endian].</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.SetValue(System.Byte[],System.Int32)">
            <summary>
            Sets the value.
            </summary>
            <param name="bytes">The bytes.</param>
            <param name="offset">The offset.</param>
        </member>
        <member name="T:NTL.VariableHandler.VariableData.ToTypeConvertion">
            <summary>
            
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.ToType">
            <summary>
            To type
            </summary>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToBoolean(System.Object)">
            <summary>
            To the boolean.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToByte(System.Object)">
            <summary>
            To the byte.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToInt16(System.Object)">
            <summary>
            To the int16.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToInt32(System.Object)">
            <summary>
            To the int32.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToUInt16(System.Object)">
            <summary>
            To the u int16.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToUInt32(System.Object)">
            <summary>
            To the u int32.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToSingle(System.Object)">
            <summary>
            To the single.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToDouble(System.Object)">
            <summary>
            To the double.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToSByte(System.Object)">
            <summary>
            To the s byte.
            </summary>
            <param name="value">The value.</param>
            <returns></returns>
        </member>
        <member name="T:NTL.VariableHandler.VariableData.ToTypeArrayConvertion">
            <summary>
            
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="F:NTL.VariableHandler.VariableData.ToTypeFromArray">
            <summary>
            To type from array
            </summary>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToBooleanFromArray(System.Byte[],System.Int32)">
            <summary>
            To the boolean from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToByteFromArray(System.Byte[],System.Int32)">
            <summary>
            To the byte from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToInt16FromArray(System.Byte[],System.Int32)">
            <summary>
            To the int16 from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToInt32FromArray(System.Byte[],System.Int32)">
            <summary>
            To the int32 from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToUInt16FromArray(System.Byte[],System.Int32)">
            <summary>
            To the u int16 from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToUInt32FromArray(System.Byte[],System.Int32)">
            <summary>
            To the u int32 from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToSingleFromArray(System.Byte[],System.Int32)">
            <summary>
            To the single from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.ToSByteFromArray(System.Byte[],System.Int32)">
            <summary>
            To the character from array.
            </summary>
            <param name="value">The value.</param>
            <param name="startIndex">The start index.</param>
            <returns></returns>
        </member>
        <member name="E:NTL.VariableHandler.VariableData.PropertyChanged">
            <summary>
            Occurs when a property value changes.
            </summary>
            <returns></returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableData.OnPropertyChanged(System.String)">
            <summary>
            Called when property changed.
            </summary>
            <param name="propertyName">Name of the property.</param>
        </member>
        <member name="M:NTL.VariableHandler.VariableDataIndexComparer.Equals(NTL.VariableHandler.VariableData,NTL.VariableHandler.VariableData)">
            <summary>
            Determines whether the specified objects are equal.
            </summary>
            <param name="x">The first object of type T to compare.</param>
            <param name="y">The second object of type T to compare.</param>
            <returns>
            true if the specified objects are equal; otherwise, false.
            </returns>
        </member>
        <member name="M:NTL.VariableHandler.VariableDataIndexComparer.GetHashCode(NTL.VariableHandler.VariableData)">
            <summary>
            Returns a hash code for this instance.
            </summary>
            <param name="obj">The object.</param>
            <returns>
            A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table. 
            </returns>
        </member>
        <member name="T:NTL.WaitableMessage`1">
            <summary>
            
            </summary>
            <typeparam name="T"></typeparam>
        </member>
        <member name="F:NTL.WaitableMessage`1.waitMessageMutex">
            <summary>
            The wait message mutex
            </summary>
        </member>
        <member name="M:NTL.WaitableMessage`1.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.WaitableMessage`1"/> class.
            </summary>
            <param name="id">The identifier.</param>
        </member>
        <member name="M:NTL.WaitableMessage`1.Wait(System.Int32)">
            <summary>
            Waits the specified timeout for this message to arrive.
            </summary>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessage`1.ReleaseWait">
            <summary>
            Releases the wait.
            Signal that this message has arrived.
            </summary>
        </member>
        <member name="P:NTL.WaitableMessage`1.ID">
            <summary>
            Gets the identifier.
            </summary>
            <value>
            The identifier.
            </value>
        </member>
        <member name="E:NTL.WaitableMessage`1.MessageMatched">
            <summary>
            Occurs when [message matched].
            </summary>
        </member>
        <member name="M:NTL.WaitableMessage`1.OnMessageMatched">
            <summary>
            Called when [message matched].
            </summary>
        </member>
        <member name="T:NTL.WaitableMessage`1.ReleaseConditionDelegate">
            <summary>
            
            </summary>
            <param name="sender">The sender.</param>
            <returns></returns>
        </member>
        <member name="P:NTL.WaitableMessage`1.ReleaseCondition">
            <summary>
            Gets or sets the wait condition. NEM TODO
            </summary>
            <value>
            The wait condition.
            </value>
        </member>
        <member name="P:NTL.WaitableMessage`1.Subscribe">
            <summary>
            Gets or sets a value indicating whether this <see cref="T:NTL.WaitableMessage`1"/> is subscribe.
            </summary>
            <value>
              <c>true</c> if subscribe; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="P:NTL.WaitableMessage`1.IgnoreLength">
            <summary>
            Gets or sets a value indicating whether [ignore length].
            </summary>
            <value>
              <c>true</c> if [ignore length]; otherwise, <c>false</c>.
            </value>
        </member>
        <member name="F:NTL.WaitableMessage`1.messageMatch">
            <summary>
            The message match
            </summary>
        </member>
        <member name="P:NTL.WaitableMessage`1.MessageMatch">
            <summary>
            Gets the message match.
            If the CompareTo returns true this is the data compared against else is null;
            </summary>
            <value>
            The message match.
            </value>
        </member>
        <member name="M:NTL.WaitableMessage`1.CompareTo(`0,System.Boolean)">
            <summary>
            Compares to the message incoming to the waitable message
            </summary>
            <param name="data">The data.</param>
            <param name="setMessageMatch">if set to <c>true</c> set message match if compare is true.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessage`1.Copy">
            <summary>
            Copies this instance.
            </summary>
            <returns></returns>
            <exception cref="T:System.NotImplementedException"></exception>
        </member>
        <member name="T:NTL.WaitableMessageQueue`1">
            <summary>
            
            </summary>
            <typeparam name="T"></typeparam>
        </member>
        <member name="F:NTL.WaitableMessageQueue`1.waitMessageQueueMutex">
            <summary>
            The wait message queue mutex
            </summary>
        </member>
        <member name="F:NTL.WaitableMessageQueue`1.messageQueue">
            <summary>
            The message queue
            </summary>
        </member>
        <member name="F:NTL.WaitableMessageQueue`1.messageQueueHandle">
            <summary>
            The message queue handle
            Can be used to lock handles.
            </summary>
        </member>
        <member name="F:NTL.WaitableMessageQueue`1.receivedMessages">
            <summary>
            The received message queue
            </summary>
        </member>
        <member name="P:NTL.WaitableMessageQueue`1.ReceivedMessages">
            <summary>
            Gets or sets the received message.
            </summary>
            <value>
            The received message.
            </value>
        </member>
        <member name="P:NTL.WaitableMessageQueue`1.MissedMessagesIDs">
            <summary>
            Gets the missed messages ids.
            </summary>
            <value>
            The missed messages i ds.
            </value>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.WaitableMessageQueue`1"/> class.
            </summary>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.AddToMessageQueue(NTL.WaitableMessage{`0},System.Boolean)">
            <summary>
            Adds to message queue.
            </summary>
            <param name="message">The message.</param>
            <param name="messageOverride">if set to <c>true</c> [message override].</param>
            <exception cref="T:System.ArgumentException">message</exception>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.ClearMessageQueue">
            <summary>
            Clears the message queue.
            </summary>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.CompareTo(`0)">
            <summary>
            Compares the incoming message against the queue.
            Returns true if the message matches and set the MessageMatch.
            </summary>
            <param name="incomingMessage">The incoming message.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.Wait(System.Int32,System.String)">
            <summary>
            Waits the specified timeout.
            </summary>
            <param name="timeout">The timeout.</param>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.DequeueReceivedMessage(System.String)">
            <summary>
            Dequeues the received message.
            </summary>
            <param name="id">The identifier.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.Wait(System.Int32)">
            <summary>
            Waits the specified timeout for this message queue to arrive.
            </summary>
            <param name="timeout">The timeout.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.ReleaseWait">
            <summary>
            Releases the wait.
            Signal that this message has arrived.
            </summary>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.GetEnumerator">
            <summary>
            Returns an enumerator that iterates through the collection.
            </summary>
            <returns>
            A <see cref="T:System.Collections.Generic.IEnumerator`1" /> that can be used to iterate through the collection.
            </returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.System#Collections#IEnumerable#GetEnumerator">
            <summary>
            Returns an enumerator that iterates through a collection.
            </summary>
            <returns>
            An <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection.
            </returns>
        </member>
        <member name="M:NTL.WaitableMessageQueue`1.ToString">
            <summary>
            Returns a <see cref="T:System.String" /> that represents this instance.
            </summary>
            <returns>
            A <see cref="T:System.String" /> that represents this instance.
            </returns>
        </member>
        <member name="F:NTL.WaitableSimpleWhirlpoolMessage.source">
            <summary>
            The source
            </summary>
        </member>
        <member name="P:NTL.WaitableSimpleWhirlpoolMessage.Source">
            <summary>
            Gets or sets the source.
            </summary>
            <value>
            The source.
            </value>
        </member>
        <member name="F:NTL.WaitableSimpleWhirlpoolMessage.destination">
            <summary>
            The destination
            </summary>
        </member>
        <member name="P:NTL.WaitableSimpleWhirlpoolMessage.Destination">
            <summary>
            Gets or sets the destination.
            </summary>
            <value>
            The destination.
            </value>
        </member>
        <member name="F:NTL.WaitableSimpleWhirlpoolMessage.sap">
            <summary>
            The sap
            </summary>
        </member>
        <member name="P:NTL.WaitableSimpleWhirlpoolMessage.SAP">
            <summary>
            Gets or sets the sap.
            </summary>
            <value>
            The sap.
            </value>
        </member>
        <member name="P:NTL.WaitableSimpleWhirlpoolMessage.Payload">
            <summary>
            Gets or sets the data.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="P:NTL.WaitableSimpleWhirlpoolMessage.PayloadMask">
            <summary>
            Gets or sets the data mask.
            </summary>
            <value>
            The data.
            </value>
        </member>
        <member name="M:NTL.WaitableSimpleWhirlpoolMessage.#ctor(System.String)">
            <summary>
            Initializes a new instance of the <see cref="T:NTL.WaitableSimpleWhirlpoolMessage"/> class.
            </summary>
            <param name="id">The identifier.</param>
        </member>
        <member name="M:NTL.WaitableSimpleWhirlpoolMessage.GetHashCode">
            <summary>
            Returns a hash code for this instance.
            </summary>
            <returns>
            A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table. 
            </returns>
        </member>
        <member name="M:NTL.WaitableSimpleWhirlpoolMessage.CompareTo(WhirlpoolCommunication.Packets.ExtendedSimpleWhirlpoolPacket,System.Boolean)">
            <summary>
            Compares to another message.
            </summary>
            <param name="data">The data.</param>
            <param name="setMessageMatch">if set to <c>true</c> set message match if compare is true.</param>
            <returns></returns>
        </member>
        <member name="M:NTL.WaitableSimpleWhirlpoolMessage.FixBinaryMask">
            <summary>
            Fixes the binary mask.
            </summary>
        </member>
    </members>
</doc>
