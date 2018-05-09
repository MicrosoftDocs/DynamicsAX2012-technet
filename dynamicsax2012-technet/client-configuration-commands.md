---
title: Client configuration commands
TOCTitle: Client configuration commands
ms:assetid: 8eceee52-a2d1-4487-80ca-27a95503c467
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569653(v=AX.60)
ms:contentKeyID: 39555384
ms.date: 10/20/2014
mtps_version: v=AX.60
---

# Client configuration commands 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Configuration commands set the options that are used when a Microsoft Dynamics AX client starts. Configuration commands can be run directly from the following locations:

  - In a configuration file

  - In the **Configuration Command to run at kernel startup** field in the Microsoft Dynamics AX 2012 Configuration utility

  - From a command prompt using Ax32.exe, which is located in the *Drive*:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Client\\Bin directory

For more information about how to run commands from these locations, see [Execute configuration commands](execute-configuration-commands.md).

## General options

Configuration commands use different syntax depending on where you execute the command. The syntax variations are provided in the following sections.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command in command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>company,Text,&lt;string&gt;</p></td>
<td><p>-<strong>company</strong>=&lt;string&gt;</p></td>
<td><p><strong>Company</strong></p></td>
<td><p>Specify the company that opens when the client starts.</p></td>
</tr>
<tr class="even">
<td><p>log,Text, &lt;path&gt;</p></td>
<td><p>-<strong>log</strong>=&lt;path&gt;</p></td>
<td><p><strong>Log directory</strong></p></td>
<td><p>Specify an alternate directory for the log files generated when you make changes in the Application Object Tree (AOT). When you execute this command from a command prompt, insert an underscore wherever a path name includes space breaks.</p></td>
</tr>
<tr class="odd">
<td><p>This command cannot be set in a file.</p></td>
<td><p>-<strong>regConfig</strong>=&lt;name of configuration&gt;</p></td>
<td><p><strong>Configuration</strong></p></td>
<td><p>Specify the configuration to use when the client starts.</p></td>
</tr>
<tr class="even">
<td><p>startupcmd,Text,&lt;command&gt;</p></td>
<td><p>-<strong>startupCmd</strong>=&lt;command&gt;</p></td>
<td><p><strong>Command to run at application startup</strong></p></td>
<td><p>Enter a <strong>SysStartupCmd</strong> method to run when the client starts. To view <strong>SysStartupCmd</strong> methods, expand the <strong>Classes</strong> node in the AOT, expand <strong>SysStartupCmd</strong>, and double-click <strong>Construct</strong>. Available commands are listed in the <strong>Switch</strong> section.</p>
<div class="alert">

> [!NOTE]
> <P>No syntax checking is performed before commands are passed to the client. Test any command before using it.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>startupmsg,Text,&lt;string&gt;</p></td>
<td><p>-<strong>startupmsg</strong>=&lt;string&gt;</p></td>
<td><p><strong>Startup message</strong></p></td>
<td><p>Specify text to display in a message box when the client starts.</p></td>
</tr>
<tr class="even">
<td><p>This command cannot be set in a file.</p></td>
<td><p>-<strong>language</strong>=&lt;string&gt;</p></td>
<td><p>This command does not have a corresponding user interface value.</p></td>
<td><p>Specify the language to use when the client starts. You must specify an alphabetical language code such as da, de, fr-ca, en-us, etc. These codes correspond to a file in the following directory: <em>Drive</em>:\Program Files (x86)\Microsoft Dynamics AX\60\Client\Bin. You must also have a valid license for the language.</p></td>
</tr>
<tr class="odd">
<td><p>This command cannot be set in a file.</p></td>
<td><p>–<strong>roamingprofile</strong></p></td>
<td><p><strong>Use roaming user profiles</strong></p></td>
<td><p>Enables Microsoft Dynamics AX client files and settings to work with roaming profiles in a Remote Desktop Services (RDS) farm. Roaming profiles can improve client startup times in an RDS farm, though results depend on network and hardware infrastructure. For more information, see <a href="improve-client-startup-times-by-configuring-clients-to-use-roaming-profiles.md">Improve client startup times by configuring clients to use roaming profiles</a>.</p></td>
</tr>
<tr class="even">
<td><p>This command cannot be set in a file.</p></td>
<td><p>-<strong>masterauc</strong>=&lt;path&gt;</p></td>
<td><p><strong>Path to global client cache file (AUC)</strong></p></td>
<td><p>Specify the location of a global client cache file (formerly known as an Application Unicode Cache file). This file will be used if no local file exists, or if the file is newer than the local file. Using this option can reduce the time to start up the MSDAX Windows client.</p></td>
</tr>
</tbody>
</table>


## Connection options

This table describes the options you can use to connect to an AOS instance.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>aos2,text,&lt;options&gt;</p>
<p>Options include:</p>
<p>host</p>
<p>–or–</p>
<p>host:port</p></td>
<td><p>-<strong>aos2</strong>=host</p>
<p>–or–</p>
<p>-<strong>aos2</strong>=host:port</p>
<p></p></td>
<td><p><strong>Add Application Object Server Instance</strong></p></td>
<td><p>Specify connections to additional AOS instances. Instance and port are optional.</p>
<p>If port is not specified, the value defaults to 2712.</p></td>
</tr>
<tr class="even">
<td><p>aosencryption,Text,&lt;0,1&gt;</p></td>
<td><p>-<strong>aosencryption</strong>=&lt;0,1&gt;</p></td>
<td><p><strong>Encrypt client to server communication</strong></p></td>
<td><p>Encrypt all data sent between this client and the AOS.</p></td>
</tr>
<tr class="odd">
<td><p>useserverprinters,Int,1</p></td>
<td><p>-<strong>useserverprinters</strong></p></td>
<td><p><strong>Connect to printers on the server</strong></p></td>
<td><p>Enable clients to connect to printers on the AOS computer. You must configure the AOS to print. For more information, see <a href="configure-an-aos-instance-to-print.md">Configure an AOS instance to print</a>.</p></td>
</tr>
</tbody>
</table>


## Developer options

This table describes the options you can use to set up the development environment.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>This command cannot be set in a file.</p></td>
<td><p>-<strong>development</strong></p></td>
<td><p>This command does not have a corresponding user interface value.</p></td>
<td><p>Opens the Microsoft Dynamics AX developer workspace and the AOT.</p></td>
</tr>
<tr class="even">
<td><p>aol,Text,&lt;string&gt;</p></td>
<td><p>-<strong>aol</strong>=&lt;string&gt;</p></td>
<td><p><strong>Layer to open in Application Object Tree</strong></p></td>
<td><p>Specifies which layer to open in the AOT.</p></td>
</tr>
<tr class="odd">
<td><p>aolcode,Text,&lt;string&gt;</p></td>
<td><p>-<strong>aolcode</strong>=&lt;string&gt;</p></td>
<td><p><strong>License code</strong></p></td>
<td><p>Specifies the developer license code for developer options.</p></td>
</tr>
<tr class="even">
<td><p>globalbreakpoints,Int,1</p></td>
<td><p>-<strong>globalbreakpoints</strong></p></td>
<td><p><strong>Enable global breakpoints for debugging code running in the Business Connector or client</strong></p></td>
<td><p>This is a binary command that is not set by default. For all users, allow X++ code running in the Business Connector or client to be interrupted by global breakpoints</p></td>
</tr>
<tr class="odd">
<td><p>Not supported in the configuration file.</p></td>
<td><p>-<strong>logstrtrunc</strong></p></td>
<td><p>Writes diagnostic information to the Windows Event Log every time an X++ str value is truncated due to the declaration having specified a maximum length.</p></td>
<td><p>Truncation of str values does not occur if the X++ code is running as .NET Framework common intermediate language (CIL). This is one of the rare cases where the behavior of X++ code differs depending on whether the code is being run as interpreted p-code versus CIL.</p></td>
</tr>
<tr class="even">
<td><p>xppdebug,Text,&lt;0,1&gt;</p></td>
<td><p>-<strong>xppdebug</strong>=&lt;0,1&gt;</p></td>
<td><p><strong>Enable user breakpoints for debugging code running in the Business Connector</strong></p></td>
<td><p>For sessions owned by users for whom debug is enabled, allow X++ code running in the Business Connector to be interrupted by breakpoints.</p></td>
</tr>
<tr class="odd">
<td><p>aotimportfile,text,&lt;file.xpo&gt;</p></td>
<td><p>–<strong>aotimportfile</strong>=&lt;File.xpo&gt;</p></td>
<td><p>This command does not have a corresponding user interface value.</p></td>
<td><p>Import an xpo file and start a full compile of the AOT when the client starts.</p></td>
</tr>
<tr class="even">
<td><p>Not supported in the configuration file.</p></td>
<td><p>-<strong>model</strong> =&lt;model to use&gt;</p></td>
<td><p>This command does not have a corresponding user interface value.</p></td>
<td><p>The “current model” is the model where all new AOT elements are created in. For this command, &lt;model-to-use&gt; is any valid model in the layer you are starting Microsoft Dynamics AX in. For example, USR. If &lt;model-to-use&gt; is not a valid model, the system generated model is used instead. For example “USR Model”.</p></td>
</tr>
<tr class="odd">
<td><p>Not supported in the configuration file.</p></td>
<td><p>-<strong>noauto</strong></p></td>
<td><p>This command does not have a corresponding user interface value.</p></td>
<td><p>Microsoft Dynamics AX developers use this parameter when they have made changes to the startup behavior of Microsoft Dynamics AX and they want to bypass those changes to troubleshoot issues or problems.</p></td>
</tr>
</tbody>
</table>


## Legacy configuration options

Microsoft Dynamics AX 2012 Configuration files include the following parameters. These parameters apply to older versions of Microsoft Dynamics AX. We recommend that you do not change values for these options because unexpected results may occur.

client,Text,thin

broadcast,Text,

native,Int,0

sqluser,Text,

sqlpwd,Text,

localappldoc,Int,0

hassqlpwd,Int,0

localsysdoc,Int,0

applexclusive,Int,1

hascompwd,Int,0

compwd,Text,

allowunauth,Int,0

windowsauth,Text,1

hasocipwd,Int,0

dbunicodeenabled,Text,1

## See also

[Client operations](client-operations.md)

[Application Object Server (AOS) configuration commands](application-object-server-aos-configuration-commands.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

