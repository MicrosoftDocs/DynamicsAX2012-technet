---
title: Setup parameters reference
TOCTitle: Setup parameters reference
ms:assetid: 474f9d72-e1e5-433a-840e-d9eb00753e94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548130(v=AX.60)
ms:contentKeyID: 35132720
ms.date: 04/14/2015
mtps_version: v=AX.60
---

# Setup parameters reference 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic lists the parameters that can be used for a silent installation. You can install any Microsoft Dynamics AX component in silent mode. For more information about how to install Microsoft Dynamics AX by using parameters, see [Run Setup in silent mode](run-setup-in-silent-mode.md).

The following installation parameters are included in this topic:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><ul>
<li><p>Common parameters</p></li>
<li><p>Analysis Services configuration parameters</p></li>
<li><p>Application Object Server parameters</p></li>
<li><p>Client parameters</p></li>
<li><p>Commerce Data Exchange: Async Client parameters</p></li>
<li><p>Commerce Data Exchange: Async Server parameters</p></li>
<li><p>Commerce Data Exchange: Real-time Service parameters</p></li>
<li><p>Commerce Data Exchange: Synch Service parameters</p></li>
<li><p>Connector parameters</p></li>
<li><p>Data Import Export Framework parameters</p></li>
<li><p>Database parameters</p></li>
<li><p>Debugger parameters</p></li>
<li><p>Enterprise Portal parameters</p></li>
<li><p>Enterprise Search parameters</p></li>
<li><p>Help Server parameters</p></li>
<li><p>Management Reporter parameters</p></li>
<li><p>Management utilities parameters</p></li>
<li><p>Modern POS parameters</p></li>
<li><p>.NET Business Connector parameters</p></li>
<li><p>Office add-ins parameters</p></li>
</ul></td>
<td><ul>
<li><p>Remote Desktop Services integration parameters</p></li>
<li><p>Report Designer parameters</p></li>
<li><p>Reporting Services extensions parameters</p></li>
<li><p>Retail channel database parameters</p></li>
<li><p>Retail Hardware Station parameters</p></li>
<li><p>Retail Headquarters parameters</p></li>
<li><p>Retail mass deployment toolkit</p></li>
<li><p>Retail online channel parameters</p></li>
<li><p>Retail POS parameters</p></li>
<li><p>Retail SDK parameters</p></li>
<li><p>Retail Server parameters</p></li>
<li><p>Retail Store Connect parameters</p></li>
<li><p>Retail Store Database Utility parameters</p></li>
<li><p>Retail Transaction Service parameters</p></li>
<li><p>Synchronization service and synchronization proxy parameters</p></li>
<li><p>Trace Parser parameters</p></li>
<li><p>Visual Studio Tools parameters</p></li>
<li><p>VSS writer parameters</p></li>
<li><p>Warehouse Mobile Devices Portal parameters</p></li>
<li><p>Web services on IIS parameters</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Common parameters

The following table lists the parameters that control the general behavior of Setup. For example, the parameters are used to specify a parameter file, display or hide the Setup wizard, and specify the location of all related files.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>AcceptLicenseTerms</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether you want to accept the terms of the license agreement.</p>
<ul>
<li><p>0 – Don’t accept the license terms.</p></li>
<li><p>1 – Accept the license terms.</p></li>
</ul>
<p>If <em>HideUI</em>=1, <em>AcceptLicenseTerms</em> must be set to 1. If <em>AcceptLicenseTerms</em>=0, an error message is displayed, and installation can’t continue.</p>
<p>If <em>HideUI</em>=0, the License Terms screen is displayed, regardless of the setting of <em>AcceptLicenseTerms</em>.</p>
<div class="alert">

> [!IMPORTANT]
> <P>Only models that are published by Microsoft are covered under the license terms for Microsoft Dynamics AX.</P>


</div></td>
</tr>
<tr class="even">
<td><p><em>LogDir</em></p></td>
<td><p>See the description.</p></td>
<td><p>Specify where the log files for the Setup, Setup Support, and Windows installers are saved.</p>
<p>By default, the following path is used:</p>
<p>%<em>&lt;Program Files&gt;</em>%\Microsoft Dynamics AX\60\Setup Logs\YYYY-MM-DD HH:MM-SS</p>
<div class="alert">

> [!NOTE]
> <P>When log files are saved to the default location, they are arranged in dated folders to protect existing log files from being overwritten. If you override the default <EM>LogDir</EM> value, the logs are saved to the exact folder that you specify. Any existing log file in that folder is overwritten.</P>


</div>
<p>The path can be fully qualified, or it can be relative to the location of the Setup.exe file. Relative paths can include upward qualifiers, such as &quot;..\..\&quot;.</p></td>
</tr>
<tr class="odd">
<td><p><em>InstallPath</em></p></td>
<td><p>%<em>ProgramFiles</em>%\Microsoft Dynamics AX\60</p></td>
<td><p>Specify the root path for all Microsoft Dynamics AX files that are installed on a computer.</p></td>
</tr>
<tr class="even">
<td><p><em>InstallPath32Bit</em></p></td>
<td><p>%<em>ProgramFiles(x86)</em>%\Microsoft Dynamics AX\60</p></td>
<td><p>Specify the root path for all 32-bit Microsoft Dynamics AX files that are installed on a computer. This parameter is valid only when you install Microsoft Dynamics AX components on a 64-bit operating system. You can’t specify the same path for both 64-bit and 32-bit files.</p></td>
</tr>
<tr class="odd">
<td><p><em>ResetIIS</em></p></td>
<td><p>1</p></td>
<td><p>Specify whether you want Internet Information Services (IIS) to be restarted after Microsoft Dynamics AX is installed.</p>
<ul>
<li><p>0 – Restart IIS after installation.</p></li>
<li><p>1 – Don’t restart IIS after installation.</p></li>
</ul>
<p>This parameter is used when you install web services on IIS, reporting extensions, and Enterprise Portal for Microsoft Dynamics AX.</p></td>
</tr>
<tr class="even">
<td><p><em>UpdatesPath</em></p></td>
<td><p>&lt;DVD directory&gt;\Updates</p></td>
<td><p>Specify the location of updates that have been downloaded for Microsoft Dynamics AX. This includes updates for the Setup application.</p></td>
</tr>
<tr class="odd">
<td><p><em>ConfigurePrerequisites</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether mandatory prerequisites are installed and configured automatically as part of Setup.</p>
<ul>
<li><p>0 – Don’t install and configure mandatory prerequisites.</p></li>
<li><p>1 – Install and configure all mandatory prerequisites.</p></li>
</ul>
<p>Setup doesn’t automatically configure optional prerequisites.</p></td>
</tr>
<tr class="even">
<td><p><em>HideUI</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Setup wizard is displayed.</p>
<ul>
<li><p>0 – Display the wizard.</p></li>
<li><p>1 – Hide the wizard, and run Setup in silent mode.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>OptInCEIP</em></p></td>
<td><p>1</p></td>
<td><p>Specify whether you want to participate in the Customer Experience Improvement Program.</p>
<ul>
<li><p>0 – Opt in to the Customer Experience Improvement Program.</p></li>
<li><p>1 – Don’t opt in to the Customer Experience Improvement Program.</p></li>
</ul>
<p>For more information about the Customer Experience Improvement Program, see <a href="http://go.microsoft.com/fwlink/?linkid=221577">http://go.microsoft.com/fwlink/?LinkId=221577</a>.</p></td>
</tr>
<tr class="even">
<td><p><em>UseMicrosoftUpdate</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether you want the current computer to participate in Microsoft Update.</p>
<ul>
<li><p>0 – Opt in to Microsoft Update.</p></li>
<li><p>1 – Don’t opt in to Microsoft Update.</p></li>
</ul>
<p>If the current computer already participates in Microsoft Update, this parameter is ignored.</p></td>
</tr>
<tr class="odd">
<td><p><em>ParmFile</em></p></td>
<td><p>None</p></td>
<td><p>Specify the path of a file that contains other parameters.</p>
<p>If you use this parameter, it must be the only parameter, and the parameter file must contain all the other parameters that you want to specify.</p>
<p>In the parameter file, each parameter's <em>Name=Value</em> combination must be on a separate line. You can use ExampleParmFile.txt, which is available in the DVD\Support folder, as an example.</p>
<div class="alert">

> [!NOTE]
> <P>Don’t include double quotation marks in parameter files. Because line returns are used as delimiters in a parameter file, values that otherwise require double quotation marks don’t require them here.</P>


</div>
<p>To prevent a line in a parameter file from being run, type a number sign (#) before the line.</p>
<p>The path can be fully qualified, or it can be relative to the location of the Setup.exe file. Relative paths can include upward qualifiers, such as &quot;..\..\&quot;.</p></td>
</tr>
<tr class="even">
<td><p><em>AcceptBestPracticesList</em></p>
<p>This option is available only with AX 2012 R3.</p></td>
<td><p>0</p></td>
<td><p>Specify that recommended best practices have been followed.</p>
<ul>
<li><p>0 – Don’t accept best practices.</p></li>
<li><p>1 – Accept best practices.</p></li>
</ul>
<p>This parameter is required if <em>InstallWarehouseServer</em>=1.</p></td>
</tr>
</tbody>
</table>


## Analysis Services configuration parameters

The following table lists the parameters that control how Setup configures Microsoft SQL Server Analysis Services for Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>ConfigureAnalysisServices</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Analysis Services is configured for Microsoft Dynamics AX.</p>
<ul>
<li><p>0 – Don’t configure Analysis Services.</p></li>
<li><p>1 – Configure Analysis Services.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>AnalysisServicesInstance</em></p></td>
<td><p><em>&lt;ServerName&gt;</em>$MSSQLServerOLAPService</p></td>
<td><p>Specify the instance of Analysis Services to connect to. The instance can be specified as a server, or as a fully qualified server and instance.</p>
<p>To specify a named instance, use the format <em>&lt;ServerName&gt;</em>$MSOLAP$<em>&lt;InstanceName&gt;</em>.</p></td>
</tr>
<tr class="odd">
<td><p><em>AnalysisServicesOLAPAccounts</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that the Analysis Services service uses to access the Microsoft Dynamics AX OLTP database. Usually, this account is the service logon account for the selected Analysis Services instance.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveAnalysisServices</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the configuration of Analysis Services for Microsoft Dynamics AX is removed.</p>
<ul>
<li><p>0 – Don’t remove the Analysis Services configuration.</p></li>
<li><p>1 – Remove the Analysis Services configuration.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Application Object Server parameters

The following table lists the parameters that control how Setup installs and removes Application Object Server (AOS).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallAos</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an instance of AOS is installed.</p>
<ul>
<li><p>0 – Don’t install an instance of AOS.</p></li>
<li><p>1 – Install an instance of AOS.</p></li>
</ul>
<p>If the setting of <em>AosInstanceName</em> matches the name of an instance that was previously installed, and <em>InstallAos</em>=1, the Windows installer runs in maintenance mode and doesn’t change any settings.</p>
<p>Up to 99 AOS instances can be installed.</p></td>
</tr>
<tr class="even">
<td><p><em>AosInstanceName</em></p></td>
<td><p>MicrosoftDynamicsAx</p></td>
<td><p>Specify the name of the AOS instance. The name must be unique.</p>
<p>This parameter is required if <em>InstallAOS</em>=1.</p>
<p>You can optionally specify this parameter when you install components that require an AOS connection, such as the client.</p></td>
</tr>
<tr class="odd">
<td><p><em>AosPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the TCP/IP port number on which the AOS instance receives requests from the client or .NET Business Connector.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p>
<p>You can optionally specify this parameter when you install components that require an AOS connection, such as the client.</p></td>
</tr>
<tr class="even">
<td><p><em>AosWsdlPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which the AOS instance receives WSDL requests.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p>
<p>You can optionally specify this parameter when you install components that require an AOS connection, such as the client.</p></td>
</tr>
<tr class="odd">
<td><p><em>AosStart</em></p></td>
<td><p>1</p></td>
<td><p>Specify whether Setup starts the AOS service after the AOS instance is installed.</p>
<ul>
<li><p>0 – Don’t start the AOS service.</p></li>
<li><p>1 – Start the AOS service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>UpgradeAos</em></p>
<p>This option is available only with AX 2012 R3 and AX 2012 R2.</p></td>
<td><p>0</p></td>
<td><p>Specify whether an instance of AOS is upgraded.</p>
<ul>
<li><p>0 – Don’t upgrade an instance of AOS.</p></li>
<li><p>1 – Upgrade an instance of AOS.</p></li>
</ul>
<p>This parameter is valid only if <em>InstallAOS</em>=1.</p>
<p>When you use this parameter, you must also supply the name of an existing AOS instance by using the <em>AosInstanceName</em> parameter. Setup uses the registry to obtain port information for the specified AOS instance. Therefore, you don’t have to include parameters for port numbers.</p></td>
</tr>
<tr class="odd">
<td><p><em>AosAccount</em></p></td>
<td><p>The Network Service account</p></td>
<td><p>Specify the account that the Windows service for AOS runs as. The AOS instance uses this account to connect to the Microsoft Dynamics AX database.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>. You can’t specify your own account or a local computer account. You can specify a managed service account that is installed on the computer. To specify a managed service account, use the format <em>domain\ServiceAccountName</em>$.</p></td>
</tr>
<tr class="even">
<td><p><em>AosAccountPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the AOS account.</p>
<p>If you use a managed service account, this parameter isn’t required.</p>
<p>If you use a standard domain account, you must specify a value for this parameter if you specify a value for the <em>AosAccount</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>AosNetTcpPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which the AOS instance receives net.tcp requests.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p></td>
</tr>
<tr class="even">
<td><p><em>AOSStartupTimeout</em></p></td>
<td><p>300</p></td>
<td><p>Specify how long, in seconds, Setup must wait for the AOS instance to start. Specify a value for this parameter if Setup can’t continue until the AOS instance starts, such as when you install Enterprise Portal at the same time.</p>
<p>Make sure that the value that you specify is large enough so that the AOS instance has time to start. If the value for this parameter is too small, some components can’t be installed.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveAos</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an installed instance of AOS is removed.</p>
<ul>
<li><p>0 – Don’t remove the AOS instance.</p></li>
<li><p>1 – Remove the AOS instance.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Client parameters

The following table lists the parameters that control how Setup installs and removes the Microsoft Dynamics AX client. You can use Setup.exe and setup parameters to perform mass deployments of clients. For more information, see [Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallClientUI</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the user interface for the client is installed.</p>
<ul>
<li><p>0 – Don’t install the client user interface.</p></li>
<li><p>1 – Install the client user interface.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ClientConfig</em></p></td>
<td><p>1</p></td>
<td><p>Specify whether the Microsoft Dynamics AX Configuration utility is installed together with the client.</p>
<p>If .NET Business Connector is installed, the Microsoft Dynamics AX Configuration utility is always installed.</p>
<ul>
<li><p>0 – Don’t install the Microsoft Dynamics AX Configuration utility.</p></li>
<li><p>1 – Install the Microsoft Dynamics AX Configuration utility.</p></li>
</ul>
<p>If <em>ClientConfig</em>=0, you must also specify a value for the <em>ClientConfigFile</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>ClientConfigFile</em></p></td>
<td><p>None</p></td>
<td><p>Specify the path of a shared configuration file for the client. This path can be local or in a shared folder that has restricted permissions. When you specify this parameter, Setup configures a desktop shortcut to the client that uses the shared configuration file.</p></td>
</tr>
<tr class="even">
<td><p><em>ClientLanguage</em></p></td>
<td><p>en-US</p></td>
<td><p>Specify the default language that is used for the client the first time that it is started, if the database hasn’t yet been initialized by the administrator.</p>
<p>This parameter is recognized only if the client user interface is being installed.</p>
<p>This parameter is ignored if the database has been initialized.</p></td>
</tr>
<tr class="odd">
<td><p><em>ClientAosServer</em></p></td>
<td><p>See the description.</p></td>
<td><p>Specify the computer that hosts the AOS instance that the client connects to.</p>
<p>This parameter is required if one of the following parameters is used:</p>
<ul>
<li><p><em>InstallClientUI</em></p></li>
<li><p><em>InstallNetBusinessConnector</em></p></li>
<li><p><em>InstallOfficeAddins</em></p></li>
<li><p><em>InstallVisualStudioTools</em></p></li>
<li><p><em>InstallAifWebServices</em></p></li>
<li><p><em>InstallSyncService</em></p></li>
<li><p><em>InstallSynchronizationProxy</em></p></li>
<li><p><em>InstallManagementUtilities</em></p></li>
<li><p><em>ConfigureAnalysisServices</em></p></li>
<li><p><em>InstallReportingServicesExtensions</em></p></li>
<li><p><em>InstallHelpServer</em></p></li>
<li><p><em>InstallSearch</em></p></li>
<li><p><em>InstallEnterprisePortal</em></p></li>
</ul>
<p>If an AOS instance has been specified for a component that is already installed on the computer, the registry settings that contain this information already exist. Therefore, this parameter is ignored.</p>
<p>If <em>InstallAos</em>=1, the name of the current computer is used.</p>
<p>If you use this parameter, you must also specify a value for <em>AosPort</em> and <em>AosWsdlPort</em>. You can optionally specify a value for <em>AosInstance</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>ClientInstallType</em></p></td>
<td><p>0</p></td>
<td><p>Specify the type of client that is installed.</p>
<ul>
<li><p>0 – Install the business user client.</p></li>
<li><p>1 – Install the developer client.</p></li>
<li><p>2 – Install the administrator client.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>CreateClientDesktopShortcut</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether a shortcut to the client is created on the desktop.</p>
<ul>
<li><p>0 – Don’t create a client shortcut on the desktop.</p></li>
<li><p>1 – Create a client shortcut on the desktop.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveClientUI</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether components for the client user interface are removed.</p>
<ul>
<li><p>0 – Don’t remove components for the client user interface.</p></li>
<li><p>1 – Remove components for the client user interface.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Commerce Data Exchange: Async Client parameters

The following table lists the parameters that control how Setup installs and removes Async Client.


> [!NOTE]
> <P>Async Client is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallSynchServiceClient</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Async Client is installed.</p>
<ul>
<li><p>0 – Don’t install Async Client.</p></li>
<li><p>1 – Install Async Client.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceClientDatabase</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the message database for Async Client.</p>
<p>If you specify a message database name that doesn’t exist, Setup creates a new message database.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceClientDatabaseServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that will host the message database for Async Client.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceClientDatabaseServerInstanceName</em></p></td>
<td><p>None</p></td>
<td><p>If needed, specify the name of the instance of SQL Server that will host the message database for Async Client.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficeUrl</em></p></td>
<td><p>None</p></td>
<td><p>Specify the URL for the instance of Async Server. Typically, the URL is in the format https://<em>&lt;ServerName&gt;</em>:<em>port</em>/<em>&lt;WebApplicationName&gt;</em>.</p>
<p>If Async Server is installed in a cluster that has a load balancer, enter the URL to the service on the load balancer.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHOUserName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that connects to Async Server. The user name must match the user name that is specified in the channel database profile.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>SynchServiceHOPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHOPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password for the user that connects to Async Server. The password must match the password that is specified in the channel database profile.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceClientServiceUserName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the user name for the user that runs the Windows service for Async Client. The user doesn’t have to be a domain account. The user can be a member of a workgroup on the local computer.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>SynchServiceClientServicePassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceClientServicePassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password for the user that runs the Windows service for Async Client.</p></td>
</tr>
<tr class="even">
<td><p><em>ChannelDatabase</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the channel database that is used with this instance of Async Client.</p>
<p>You can connect to an existing channel database only. Setup doesn’t create a new channel database if you enter a channel database name that doesn’t exist.</p></td>
</tr>
<tr class="odd">
<td><p><em>ChannelDatabaseServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the channel database that is used with this instance of Async Client.</p></td>
</tr>
<tr class="even">
<td><p><em>ChannelDatabaseServerNamedInstanceName</em></p></td>
<td><p>None</p></td>
<td><p>If needed, specify the name of the instance of SQL Server that hosts the channel database that is used with this instance of Async Client.</p></td>
</tr>
<tr class="odd">
<td><p><em>DataStore</em></p></td>
<td><p>None</p></td>
<td><p>Specify the identifier in Microsoft Dynamics AX for the channel database that is used by tposhe selected instance of Async Client.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveSynchServiceClient</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Async Client is removed.</p>
<ul>
<li><p>0 – Don’t remove Async Client.</p></li>
<li><p>1 – Remove Async Client.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Commerce Data Exchange: Async Server parameters

The following table lists the parameters that control how Setup installs and removes Async Server.


> [!NOTE]
> <P>Async Server is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallSynchServiceHeadOffice</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Async Server is installed.</p>
<ul>
<li><p>0 – Don’t install Async Server.</p></li>
<li><p>1 – Install Async Server.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeHttpsPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Async Server receives HTTPS requests.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficeApplicationName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the web application that hosts Async Server.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeAppPoolName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the application pool that the web application runs under.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficeWebsiteName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the website that Async Server runs on.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeUsername</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that runs the application pool for Async Server.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>SynchServiceHeadOfficePassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficePassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password of the user that runs the application pool for Async Server.</p>
<p>This parameter is required if you specify a value for the <em>SynchServiceHeadOfficeUsername</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeSslCertThumbprint</em></p></td>
<td><p>None</p></td>
<td><p>Specify the thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficeDatabase</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the message database that is used with this instance of Async Server.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeDatabaseServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the message database that is used with this instance of Async Server.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceDatabaseServerInstanceName</em></p></td>
<td><p>None</p></td>
<td><p>If needed, specify the name of the instance of SQL Server that hosts the message database that is used with this instance of Async Server.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchServiceHeadOfficeTcpPort</em></p></td>
<td><p>None</p></td>
<td><p>(Optional) Specify the port on which Async Server receives TCP requests. Specify a TCP port if your environment uses high-performance data synchronization.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchServiceHeadOfficeAOSServiceUser</em></p></td>
<td><p>None</p></td>
<td><p>Specify the user account that the instance of Microsoft Dynamics AX AOS runs as.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveSynchServiceHeadOffice</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Async Server is removed.</p>
<ul>
<li><p>0 – Don’t remove Async Server.</p></li>
<li><p>1 – Remove Async Server.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Commerce Data Exchange: Real-time Service parameters

The following table lists the parameters that control how Setup installs and removes Real-time Service.

These parameters apply only to Real-time Service in Microsoft Dynamics AX 2012 R2 or AX 2012 R3. In Microsoft Dynamics AX 2012 Feature Pack, Real-time Service is called Retail Transaction Service, and the parameter names are different. For more information, see Retail Transaction Service parameters.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallCDERS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Real-time Service is installed.</p>
<ul>
<li><p>0 – Don’t install Real-time Service.</p></li>
<li><p>1 – Install Real-time Service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RealtimeServiceApplicationName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the web application that hosts Real-time Service.</p></td>
</tr>
<tr class="odd">
<td><p><em>RealtimeServiceWebsiteName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the website that Real-time Service runs on.</p></td>
</tr>
<tr class="even">
<td><p><em>RealtimeServiceAppPoolName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the application pool that the web application runs under.</p></td>
</tr>
<tr class="odd">
<td><p><em>RealtimeServiceAppPoolUsername</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that runs the application pool for Real-time Service.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>RealtimeServiceAppPoolPassword</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RealtimeServiceAppPoolPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account that runs the application pool.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>RealtimeServiceAppPoolUsername</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>RealtimeServiceHttpsPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Real-time Service receives HTTPS requests.</p></td>
</tr>
<tr class="even">
<td><p><em>RealtimeServiceSslCertThumbprint</em></p></td>
<td><p>None</p></td>
<td><p>Specify the thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
</tr>
<tr class="odd">
<td><p><em>RealtimeServiceTcpPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which Real-time Service receives net.tcp requests.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveCDERS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Real-time Service is removed.</p>
<ul>
<li><p>0 – Don’t remove Real-time Service.</p></li>
<li><p>1 – Remove Real-time Service.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Commerce Data Exchange: Synch Service parameters

The following table lists the parameters that control how Setup installs and removes Synch Service.

These parameters apply only to Synch Service in Microsoft Dynamics AX 2012 R2. In Microsoft Dynamics AX 2012 Feature Pack, Synch Service is called Retail Store Connect, and the parameter names are different. For more information, see Retail Store Connect parameters.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallCDESS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Synch Service is installed.</p>
<ul>
<li><p>0 – Don’t install Synch Service.</p></li>
<li><p>1 – Install Synch Service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>CDESSDBServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server where the message database for Synch Service will be created.</p></td>
</tr>
<tr class="odd">
<td><p><em>CDESSDatabaseName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the SQL Server database to create for Synch Service messages.</p></td>
</tr>
<tr class="even">
<td><p><em>CDESSUsername</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that the Windows service for Synch Service runs as.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>CDESSPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>CDESSPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account that runs the Windows service for Synch Service.</p>
<p>This parameter is required if you specify a value for the <em>CDESSUsername</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveCDESS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Synch Service is removed.</p>
<ul>
<li><p>0 – Don’t remove Synch Service.</p></li>
<li><p>1 – Remove Synch Service.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Connector parameters

The following table lists the parameters that control how Setup installs and removes Connector for Microsoft Dynamics.


> [!NOTE]
> <P>Connector is available through Setup only in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallConnector</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Connector is installed.</p>
<ul>
<li><p>0 – Don’t install Connector.</p></li>
<li><p>1 – Install Connector.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ConnectorAosName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the AOS instance that Connector will connect to.</p></td>
</tr>
<tr class="odd">
<td><p><em>ConnectorAosPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which the AOS instance that is used by Connector receives TCP/IP requests.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p></td>
</tr>
<tr class="even">
<td><p><em>IntegrationUserAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that is used to run integrations between Microsoft Dynamics CRM and Microsoft Dynamics AX.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>IntegrationUserPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>IntegrationUserPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the Connector integration account.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>IntegrationUserAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>IntegrationUserId</em></p></td>
<td><p>AXIntUsr</p></td>
<td><p>Enter the Microsoft Dynamics AX user ID of the integration user.</p></td>
</tr>
<tr class="odd">
<td><p><em>UseExistingAccount</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the integration user account already exists in Microsoft Dynamics AX.</p>
<ul>
<li><p>0 – Don’t use an existing account.</p></li>
<li><p>1 – Use an existing account.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ConnectorServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the database server that will host the Microsoft Dynamics Integration (MSDI) database.</p>
<div class="alert">

> [!NOTE]
> <P>The MSDI database isn’t required to be on the same computer as Connector for Microsoft Dynamics.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><em>RemoveConnector</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Connector is removed.</p>
<ul>
<li><p>0 – Don’t remove Connector.</p></li>
<li><p>1 – Remove Connector.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Data Import Export Framework parameters

The following table lists the parameters that control how Setup installs and removes the components of Data Import Export Framework.


> [!NOTE]
> <P>Data Import Export Framework is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallDIXFService</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Data Import Export Framework service is installed.</p>
<ul>
<li><p>0 – Don’t install the Data Import Export Framework service.</p></li>
<li><p>1 – Install the Data Import Export Framework service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>DIXFServiceAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that is used to run the Data Import Export Framework service. We recommend that you use the same service account as that used for the AOS service.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>DIXFServiceAccountPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>DIXFServiceAccountPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the Data Import Export Framework service account.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>DIXFServiceAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>DIXFHostName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that runs the Data Import Export Framework service.</p>
<p>This parameter is required if <em>InstallDIXFServer</em>=1 or <em>InstallDIXFClient</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>InstallDIXFServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the AOS component of Data Import Export Framework is installed.</p>
<ul>
<li><p>0 – Don’t install the AOS component of Data Import Export Framework.</p></li>
<li><p>1 – Install the AOS component of Data Import Export Framework.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>InstallDIXFClient</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the client component of Data Import Export Framework is installed.</p>
<ul>
<li><p>0 – Don’t install the client component of Data Import Export Framework.</p></li>
<li><p>1 – Install the client component of Data Import Export Framework.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>RemoveDIXFService</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Data Import Export Framework service is removed.</p>
<ul>
<li><p>0 – Don’t remove the Data Import Export Framework service.</p></li>
<li><p>1 – Remove the Data Import Export Framework service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveDIXFServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the AOS component of Data Import Export Framework is removed.</p>
<ul>
<li><p>0 – Don’t remove the AOS component of Data Import Export Framework.</p></li>
<li><p>1 – Remove the AOS component of Data Import Export Framework.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>RemoveDIXFClient</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the client component of Data Import Export Framework is removed.</p>
<ul>
<li><p>0 – Don’t remove the client component of Data Import Export Framework.</p></li>
<li><p>1 – Remove the client component of Data Import Export Framework.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Database parameters

The following table lists the parameters that control how Setup interacts with the Microsoft Dynamics AX databases.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallDatabase</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Microsoft Dynamics AX database is created.</p>
<ul>
<li><p>0 – Don’t create the database.</p></li>
<li><p>1 – Create the database, unless a database of the same name already exists.</p></li>
<li><p>2 – Create or replace the database.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>DbSqlServer</em></p></td>
<td><p>The default database instance on the local computer</p></td>
<td><p>Specify the instance of SQL Server to connect to. The instance can be specified as a server, or as a fully qualified server and instance.</p>
<p>This parameter is valid and required only if <em>InstallDatabase</em> &gt; 0, or if <em>InstallAos</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>DbSqlDatabaseName</em></p></td>
<td><p>MicrosoftDynamicsAx</p></td>
<td><p>Specify the name of the SQL Server database.</p>
<p>The database name must not include spaces or any of the following characters: backslashes (\), slashes (/), periods (.), commas (,), colons (:), brackets ([ ]), parentheses (( )), or hyphens (-).</p>
<p>This parameter is valid and required only if <em>InstallDatabase</em> &gt; 0.</p></td>
</tr>
<tr class="even">
<td><p><em>SkipSignatureVerification</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether digital signatures for model files are verified.</p>
<ul>
<li><p>0 – Verify digital signatures for model files.</p></li>
<li><p>1 – Don’t verify digital signatures for model files.</p></li>
</ul>
<div class="alert">
<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>If you import an unsigned model file to the model store, you create a security risk. We recommend that you not use this parameter unless you are confident that a model file is safe to install.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><em>DbSqlModelStoreBaseline</em></p></td>
<td><p>MicrosoftDynamicsAxBaseline</p></td>
<td><p>Specify the name of the database that is used for the baseline model store.</p>
<div class="alert">

> [!WARNING]
> <P>Don’t use this parameter. We recommend that you install the baseline model store by using the Setup wizard.</P>


</div></td>
</tr>
<tr class="even">
<td><p><em>DbConnectionTimeout</em></p></td>
<td><p>The default value for the database</p></td>
<td><p>Specify the time-out value for the database connection. The value that you set overrides the default value for the database connection time-out, 30 seconds. In most cases, we recommend that you not change this value. However, if the database server is on a remote computer, you may have to increase the time that is allowed for Setup to connect to the database.</p></td>
</tr>
<tr class="odd">
<td><p><em>AdditionalModelFiles</em></p></td>
<td><p>None</p></td>
<td><p>Specify the optional models to install. To include multiple model files, separate the values by using a semicolon (;). If this parameter isn’t specified, no optional models are installed.</p>
<p>If an optional model file isn’t located in the DVD\Models folder, you must specify the full path of the file.</p>
<p>For example: <em>AdditionalModelFiles</em>=&lt;Drive&gt;:\&lt;FolderLocation&gt;\&lt;model&gt;.model</p>
<div class="alert">

> [!IMPORTANT]
> <P>Only models that are published by Microsoft are covered under the license terms for Microsoft Dynamics AX.</P>


</div></td>
</tr>
<tr class="even">
<td><p><em>UpgradeDB</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the database that an AOS instance connects to is marked for upgrade.</p>
<ul>
<li><p>0 – Don’t mark the database for an upgrade.</p></li>
<li><p>1 – Mark the database for an upgrade.</p></li>
</ul>
<p>When you use this parameter, you must also supply the name of an AOS instance by using the <em>AosInstanceName</em> parameter. Setup uses the registry to obtain port information for the specified AOS instance. Therefore, you don’t have to include parameters for port numbers.</p></td>
</tr>
<tr class="odd">
<td><p><em>ModelStoreBackupDir</em></p>
<p>This option is available only with AX 2012 R3 and AX 2012 R2.</p></td>
<td><p>None</p></td>
<td><p>Specify the location where the model store backup file is created during a database upgrade.</p>
<p>Make sure to select a drive with sufficient disk space for the model store backup.</p>
<p>If you specify a value for this parameter, you don’t have to specify a value for the parameter <em>ModelStoreBackupFile</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>ModelStoreBackupFile</em></p>
<p>This option is available only with AX 2012 R3 and AX 2012 R2.</p></td>
<td><p>None</p></td>
<td><p>Use this parameter to import an existing model store backup file that has already been upgraded. Setup will import the backup file into the model store.</p>
<p>If you specify a value for this parameter, you don’t have to specify a value for the parameter <em>ModelStoreBackupDir</em>.</p></td>
</tr>
</tbody>
</table>


## Debugger parameters

The following table lists the parameters that control how Setup installs and removes the Microsoft Dynamics AX debugger.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallDebugger</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the debugger is installed.</p>
<ul>
<li><p>0 – Don’t install the debugger.</p></li>
<li><p>1 – Install the debugger.</p></li>
</ul>
<p>The debugger can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveDebugger</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the debugger is removed.</p>
<ul>
<li><p>0 – Don’t remove the debugger.</p></li>
<li><p>1 – Remove the debugger.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Enterprise Portal parameters

The following table lists the parameters that control how Setup installs and removes Enterprise Portal.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallEnterprisePortal</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether components for Enterprise Portal are installed.</p>
<ul>
<li><p>0 – Don’t install Enterprise Portal.</p></li>
<li><p>1 – Install Enterprise Portal.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>EnterprisePortalWebSite</em></p></td>
<td><p>None</p></td>
<td><p>Specify the website that is configured for Enterprise Portal on the local computer. This parameter is required if <em>InstallEnterprisePortal</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>EnterprisePortalCreateWebSite</em></p></td>
<td><p>1</p></td>
<td><p>Specify whether a website for Enterprise Portal is configured by using Microsoft SharePoint 2013 Products:</p>
<ul>
<li><p>0 – Don’t create a site.</p></li>
<li><p>1 – Create a site.</p></li>
<li><p>2 – Overwrite the existing site.</p></li>
</ul>
<div class="alert">

> [!NOTE]
> <P>If you use this parameter when you install Enterprise Portal, you can use only one URL per website. If you want to use multiple URLs for a website, you must install Enterprise Portal by using the Setup wizard.</P>


</div></td>
</tr>
<tr class="even">
<td><p><em>EnterprisePortalConfigureForWss</em></p></td>
<td><p>1</p></td>
<td><p>Specifies whether to configure the virtual server for Enterprise Portal.</p>
<ul>
<li><p>0 – Don’t configure the virtual server.</p></li>
<li><p>1 – Configure the virtual server.</p></li>
</ul>
<p>If this parameter is set to 1, Setup configures the application pool to run as the user of the .NET Business Connector proxy. Additionally, Setup verifies that NTLM authentication is enabled.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveEnterprisePortal</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an installed instance of Enterprise Portal is removed.</p>
<ul>
<li><p>0 – Don’t remove Enterprise Portal.</p></li>
<li><p>1 – Remove Enterprise Portal.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Enterprise Search parameters

The following table lists the parameters that control how Setup installs and removes Enterprise Search.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallSearch</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Enterprise Search is installed.</p>
<ul>
<li><p>0 – Don’t install Enterprise Search.</p></li>
<li><p>1 – Install Enterprise Search.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ContentAccessAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that the search service runs as. Enterprise Search uses this account to crawl the data in the Microsoft Dynamics AX database.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>You can’t specify your own account or a local computer account.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>ContentAccessAccountPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>ContentAccessAccountPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account for the search crawler.</p>
<p>If you use a standard domain account, you must specify a value for this parameter if you specify a value for the <em>ContentAccessAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveSearch</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an installed instance of Enterprise Search is removed.</p>
<ul>
<li><p>0 – Don’t remove Enterprise Search.</p></li>
<li><p>1 – Remove Enterprise Search.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Help Server parameters

The following table lists the parameters that control how Setup installs and removes Help Server.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallHelpServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Help Server is installed.</p>
<ul>
<li><p>0 – Don’t install Help Server.</p></li>
<li><p>1 – Install Help Server.</p></li>
</ul>
<p>If you install Help Server, you must also specify a value for <em>ClientAosServer</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>HelpServerWebSite</em></p></td>
<td><p>0</p></td>
<td><p>Specify the website that is configured for Help Server on the local computer. This parameter is required if <em>InstallHelpServer</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>HelpServerPhysicalDirectory</em></p></td>
<td><p>0</p></td>
<td><p>Specify the location of the physical directory of the website.</p></td>
</tr>
<tr class="even">
<td><p><em>HelpServerAccount</em></p></td>
<td><p>0</p></td>
<td><p>Specify the account that is used for the application pool of the Help Server website.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>You can’t specify your own account or a local computer account.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>HelpServerAccountPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>HelpServerAccountPassword</em></p></td>
<td><p>0</p></td>
<td><p>Specify the password that is associated with the account for the Help Server application pool. Help Server uses this account to access the Help content on the web server.</p>
<p>If you use a standard domain account, you must specify a value for this parameter if you specify a value for the <em>HelpServerAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>HelpServerInstallContent</em></p></td>
<td><p>None</p></td>
<td><p>Specify the Help collections and languages that are installed.</p>
<p>To include multiple collections or languages, separate the values by using a semicolon (;).</p>
<p>The U.S. English (en) version of the <strong>Application user Help</strong> collection is required. If you install another language, and the required collection was not previously installed, the collection is automatically installed together with the language that you install.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveHelpServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Help Server is removed.</p>
<ul>
<li><p>0 – Don’t remove Help Server.</p></li>
<li><p>1 – Remove Help Server and all Help content that was provided by Microsoft. Customized Help content that was created for your organization isn’t removed.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Management Reporter parameters

The following table lists the parameters that control how Setup installs and removes Management Reporter for Microsoft Dynamics ERP.


> [!NOTE]
> <P>Management Reporter for Microsoft Dynamics ERP is available through Setup only in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallManagementReporter</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Management Reporter is installed.</p>
<ul>
<li><p>0 – Don’t install Management Reporter</p></li>
<li><p>1 – Install Management Reporter.</p></li>
</ul>
<p>When you install Management Reporter, you must specify values for the parameters <em>DbSqlServer</em> and <em>DbSqlDatabaseName</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>ManagementReporterServerPort</em></p></td>
<td><p>4712</p></td>
<td><p>Specify the port that Management Reporter uses for communication.</p></td>
</tr>
<tr class="odd">
<td><p><em>ManagementAosServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the AOS instance that Management Reporter will connect to.</p></td>
</tr>
<tr class="even">
<td><p><em>ManagementAosPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which the AOS instance that is used by Management Reporter receives TCP/IP requests.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p></td>
</tr>
<tr class="odd">
<td><p><em>ManagementAosNetTcpPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port number on which the AOS instance that is used by Management Reporter receives net.tcp requests.</p>
<p>This parameter must be set to a numeric value between 1 and 65535.</p></td>
</tr>
<tr class="even">
<td><p><em>DataMartDbName</em></p></td>
<td><p>ManagementReporterDM</p></td>
<td><p>Specify the name of the database that hosts the data mart for the Management Reporter integration.</p></td>
</tr>
<tr class="odd">
<td><p><em>ManagementReporterDbName</em></p></td>
<td><p>ManagementReporter</p></td>
<td><p>Specify the name of the Management Reporter database.</p></td>
</tr>
<tr class="even">
<td><p><em>IntegrationUserAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that is used to run integrations between Management Reporter and Microsoft Dynamics AX.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>IntegrationUserPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>IntegrationUserPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the Management Reporter integration account.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>IntegrationUserAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>IntegrationUserId</em></p></td>
<td><p>AXIntUsr</p></td>
<td><p>Enter the Microsoft Dynamics AX user ID of the integration user.</p></td>
</tr>
<tr class="odd">
<td><p><em>UseExistingAccount</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the integration user account already exists in Microsoft Dynamics AX.</p>
<ul>
<li><p>0 – Don’t use an existing account.</p></li>
<li><p>1 – Use an existing account.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ManagementServiceUserAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the service account for Management Reporter. We recommend that you use the AOS service account.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>ManagementServiceUserPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>ManagementServiceUserPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the Management Reporter service account.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>ManagementServiceUserAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveManagementReporter</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Management Reporter is removed.</p>
<ul>
<li><p>0 – Don’t remove Management Reporter.</p></li>
<li><p>1 – Remove Management Reporter.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Management utilities parameters

The following table lists the parameters that control how Setup installs and removes the management utilities.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallManagementUtilities</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the management utilities are installed.</p>
<ul>
<li><p>0 – Don’t install the management utilities.</p></li>
<li><p>1 – Install the management utilities.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveManagementUtilities</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the management utilities are removed.</p>
<ul>
<li><p>0 – Don’t remove the management utilities.</p></li>
<li><p>1 – Remove the management utilities.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Modern POS parameters

The following table lists the parameters that control how Setup installs and removes Retail Modern POS.


> [!NOTE]
> <P>Retail Modern POS is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailModernPOS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Modern POS files are installed.</p>
<ul>
<li><p>0 – Don’t install Retail Modern POS files.</p></li>
<li><p>1 – Install Retail Modern POS files.</p></li>
</ul>
<p>If <em>InstallRetailModernPOS</em>=1, the installation files are extracted, but the app isn’t installed or configured. To fully install and configure Retail Modern POS, you must also include the parameter <em>RetailModernPOSIsConfigured</em>=True.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailModernPOSIsConfigured</em></p></td>
<td><p>None</p></td>
<td><p>Specify whether the Retail Modern POS app is configured.</p>
<p>Set this parameter to True to configure the Retail Modern POS app. Always use this parameter together with the <em>InstallRetailModernPOS</em> parameter.</p>
<p>Omit this parameter if you don’t want to configure the Retail Modern POS app.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailModernPOSSideloadingKey</em></p></td>
<td><p>None</p></td>
<td><p>If necessary, specify a sideloading key to deploy the app.</p>
<p>A sideloading key may be required when you install Retail Modern POS on devices that are not joined to a domain.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveRetailModernPOS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Modern POS is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail Modern POS.</p></li>
<li><p>1 – Remove Retail Modern POS.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## .NET Business Connector parameters

The following table lists the parameters that control how Setup installs and removes components for .NET Business Connector.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallNetBusinessConnector</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether .NET Business Connector is installed.</p>
<ul>
<li><p>0 – Don’t install .NET Business Connector.</p></li>
<li><p>1 – Install .NET Business Connector.</p></li>
</ul>
<p>.NET Business Connector can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>BusinessConnectorProxyAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that is used as the .NET Business Connector proxy.</p>
<p>This parameter is required if <em>InstallTraceParser</em>=1.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>BusinessConnectorProxyAccountPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>BusinessConnectorProxyAccountPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account for the .NET Business Connector proxy.</p>
<p>If you use a standard domain account, this parameter is required if the <em>BusinessConnectorProxyAccount</em> parameter is required. If a value is specified for this parameter, the value can’t be blank.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveNetBusinessConnector</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether .NET Business Connector is removed.</p>
<ul>
<li><p>0 – Don’t remove .NET Business Connector.</p></li>
<li><p>1 – Remove .NET Business Connector.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Office Add-ins parameters

The following table lists the parameters that control how Setup installs and removes Office Add-ins for Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallOfficeAddins</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Office Add-ins are installed.</p>
<ul>
<li><p>0 – Don’t install Office Add-ins.</p></li>
<li><p>1 – Install Office Add-ins.</p></li>
</ul>
<p>If <em>InstallOfficeAddins</em>=1, the components for the Remote Desktop Services integration are also installed automatically.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveOfficeAddins</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Office Add-ins are removed.</p>
<ul>
<li><p>0 – Don’t remove Office Add-ins.</p></li>
<li><p>1 – Remove Office Add-ins.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Remote Desktop Services integration parameters

The following table lists the parameters that control how Setup installs and removes the Remote Desktop Services integration.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRemoteDesktopServicesIntegration</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Remote Desktop Services integration is installed.</p>
<ul>
<li><p>0 – Don’t install the Remote Desktop Services integration.</p></li>
<li><p>1 – Install the Remote Desktop Services integration.</p></li>
</ul>
<p>If <em>InstallOfficeAddins</em>=1, the components for the Remote Desktop Services integration are installed automatically.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveRemoteDesktopServicesIntegration</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Remote Desktop Services integration is removed.</p>
<ul>
<li><p>0 – Don’t remove the Remote Desktop Services integration.</p></li>
<li><p>1 – Remove the Remote Desktop Services integration.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Report Designer parameters

The following table lists the parameters that control how Setup installs and removes Report Designer for Management Reporter.


> [!NOTE]
> <P>Report Designer is available through Setup only in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallReportDesigner</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Report Designer is installed.</p>
<ul>
<li><p>0 – Don’t install Report Designer</p></li>
<li><p>1 – Install Report Designer.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ManagementReporterServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server where Management Reporter is installed. This parameter is required only if <em>InstallReportDesigner</em> = 1.</p>
<p>If you specify a value for this parameter, you must also specify a value for <em>ManagementReporterServerPort</em>.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveReportDesigner</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Report Designer is removed.</p>
<ul>
<li><p>0 – Don’t remove Report Designer.</p></li>
<li><p>1 – Remove Report Designer.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Reporting Services extensions parameters

The following table lists the parameters that control how Setup installs and removes the reporting extensions for Microsoft SQL Server Reporting Services.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallReportingServicesExtensions</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the reporting extensions are installed.</p>
<ul>
<li><p>0 – Don’t install the reporting extensions.</p></li>
<li><p>1 – Install the reporting extensions.</p></li>
</ul>
<p>Reporting Services extensions can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>ReportingServicesInstance</em></p></td>
<td><p>The first instance of Reporting Services</p></td>
<td><p>Specify the instances of Reporting Services that are configured. This parameter is required if more than one instance of Reporting Services is installed on a computer.</p>
<div class="alert">

> [!NOTE]
> <P>If you specify a named instance, you must type the name by using all uppercase letters.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><em>RemoveReportingServicesExtensions</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the reporting extensions are removed.</p>
<ul>
<li><p>0 – Don’t remove the reporting extensions.</p></li>
<li><p>1 – Remove the reporting extensions.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Channel Configuration Utility (Retail Store Database Utility) parameters

The following table lists the parameters that control how Setup installs and removes the Retail Channel Configuration Utility.


> [!NOTE]
> <P>In AX 2012 R2 and AX 2012 Feature Pack, the Retail Channel Configuration Utility is called the Retail Store Database Utility.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailStoreDBUtil</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail Channel Configuration Utility is installed.</p>
<ul>
<li><p>0 – Don’t install the Retail Channel Configuration Utility.</p></li>
<li><p>1 – Install the Retail Channel Configuration Utility.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveRetailStoreDBUtil</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail Channel Configuration Utility is removed.</p>
<ul>
<li><p>0 – Don’t remove the Retail Channel Configuration Utility.</p></li>
<li><p>1 – Remove the Retail Channel Configuration Utility.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail channel database parameters

The following table lists the parameters that control how Setup installs and removes a retail channel database.


> [!NOTE]
> <P>Retail channel database is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailChannelDatabase</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether a retail channel database is installed.</p>
<ul>
<li><p>0 – Don’t install a retail channel database.</p></li>
<li><p>1 – Install a retail channel database.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>ChannelDatabaseName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the SQL Server database.</p>
<p>This parameter is required if <em>InstallRetailChannelDatabase</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>ChannelDatabaseServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the channel database.</p></td>
</tr>
<tr class="even">
<td><p><em>ChannelDatabaseServerInstanceName</em></p></td>
<td><p>None</p></td>
<td><p>If needed, specify the name of the instance of SQL Server that will host the channel database.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveRetailChannelDatabase</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether a retail channel database is removed.</p>
<ul>
<li><p>0 – Don’t remove a retail channel database.</p></li>
<li><p>1 – Remove a retail channel database</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Hardware Station parameters

The following table lists the parameters that control how Setup installs and removes Retail Hardware Station.


> [!NOTE]
> <P>Retail Hardware Station is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailHardwareStation</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether a Retail Hardware Station is installed.</p>
<ul>
<li><p>0 – Don’t install a Retail Hardware Station.</p></li>
<li><p>1 – Install a Retail Hardware Station.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RetailHardwareStationHttpsPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Retail Hardware Station receives HTTPS requests.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailHardwareStationHttpPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Retail Hardware Station receives HTTP requests.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailHardwareStationApplicationName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the web application that hosts Retail Hardware Station.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailHardwareStationAppPoolName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the application pool that the web application runs under.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailHardwareStationWebsiteName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the website that Retail Hardware Station runs on.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailHardwareStationAppPoolUsername</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that runs the application pool for Retail Hardware Station.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>RetailHardwareStationAppPoolPassword</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailHardwareStationAppPoolPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account that runs the application pool.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>RetailHardwareStationAppPoolUsername</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailHardwareStationSslCertThumbprint</em></p></td>
<td><p>None</p></td>
<td><p>Specify the thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveRetailHardwareStation</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether a Retail Hardware Station is removed.</p>
<ul>
<li><p>0 – Don’t remove a Retail Hardware Station.</p></li>
<li><p>1 – Remove a Retail Hardware Station.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail headquarters parameters

The following table lists the parameters that control how Setup installs and removes Retail Headquarters.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailHQ</em></p></td>
<td><p>0</p></td>
<td><p>Specify whetherRetail Headquarters is installed.</p>
<ul>
<li><p>0 – Don’t install Retail Headquarters.</p></li>
<li><p>1 – Install Retail Headquarters.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>UninstallRetailHQ</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Headquarters is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail Headquarters.</p></li>
<li><p>1 – Remove Retail Headquarters.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail mass deployment toolkit parameters

The following table lists the parameters that control how Setup installs and removes the Retail mass deployment toolkit.


> [!NOTE]
> <P>Retail mass deployment toolkit is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailScaleOutDeployment</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail mass deployment toolkit is installed.</p>
<ul>
<li><p>0 – Don’t install the Retail mass deployment toolkit.</p></li>
<li><p>1 – Install the Retail mass deployment toolkit.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveRetailScaleoutDeployment</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail mass deployment toolkit is removed.</p>
<ul>
<li><p>0 – Don’t remove the Retail mass deployment toolkit.</p></li>
<li><p>1 – Remove the Retail mass deployment toolkit.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail online channel parameters

The following table lists the parameters that control how Setup installs and removes Retail online channel.


> [!NOTE]
> <P>Retail online channel is available through Setup only in Microsoft Dynamics AX 2012 R2 or AX 2012 R3. In AX 2012 R2, only the <EM>InstallRetailOC</EM> and <EM>RemoveRetailOC</EM> parameters are available.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailOC</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail online channel is installed.</p>
<ul>
<li><p>0 – Don’t install Retail online channel.</p></li>
<li><p>1 – Install Retail online channel.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RetailOCChannelOperatingUnitNumber</em></p></td>
<td><p>None</p></td>
<td><p>Specify the identifier of the channel operating unit.</p>
<p>A channel operating unit number is specified when you create an online channel in Microsoft Dynamics AX. You must create the channel before you deploy the Retail online store. To locate the operating unit number, click <strong>Retail</strong> &gt; <strong>Retail channels</strong> &gt; <strong>Online stores</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailOCSSLCertPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password for the .pfx file.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailOCSSLCertPath</em></p></td>
<td><p>None</p></td>
<td><p>Specify the path of the .pfx file for the SSL certificate.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailOCPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>RetailOCUserName</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailOCUserName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of a domain user that has permission to create web applications and run Windows PowerShell scripts in SharePoint.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>RetailOCPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailOCChannelDBName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the channel database that is used with the online store.</p>
<p>You can connect to an existing channel database only. Setup doesn’t create a new channel database if you enter a channel database name that doesn’t exist.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailOCDBServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the channel database.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailOCDBServerNamedInstanceName</em></p></td>
<td><p></p></td>
<td><p>If needed, specify the name of the instance of SQL Server that hosts the channel database that is used with this instance of online store.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailOCStorefrontName</em></p></td>
<td><p>None</p></td>
<td><p>Specify a Retail starter store to deploy.</p>
<ul>
<li><p>Contoso – Deploy the Contoso store. The Contoso starter store is modeled after an online electronics retailer.</p></li>
<li><p>Fabrikam – Deploy the Fabrikam store. The Fabrikam starter store is modeled after an online clothing retailer.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>RemoveRetailOC</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail online channel is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail online channel.</p></li>
<li><p>1 – Remove Retail online channel.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail POS parameters

The following table lists the parameters that control how Setup installs and removes Retail POS (point of sale).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailPOS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail POS is installed.</p>
<ul>
<li><p>0 – Don’t install Retail POS.</p></li>
<li><p>1 – Install Retail POS.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>UninstallRetailPOS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail POS is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail POS.</p></li>
<li><p>1 – Remove Retail POS.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail SDK parameters

The following table lists the parameters that control how Setup installs and removes the Retail SDK.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailSDK</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail SDK is installed.</p>
<ul>
<li><p>0 – Don’t install the Retail SDK.</p></li>
<li><p>1 – Install the Retail SDK.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveRetailSDK</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the Retail SDK is removed.</p>
<ul>
<li><p>0 – Don’t remove the Retail SDK.</p></li>
<li><p>1 – Remove the Retail SDK.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Server parameters

The following table lists the parameters that control how Setup installs and removes Retail Server.


> [!NOTE]
> <P>Retail Server is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Server is installed.</p>
<ul>
<li><p>0 – Don’t install Retail Server.</p></li>
<li><p>1 – Install Retail Server.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RetailServerHttpsPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Retail Server receives HTTPS requests.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailServerHttpPort</em></p></td>
<td><p>None</p></td>
<td><p>Specify the port on which Retail Server receives HTTP requests.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailServerApplicationName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the web application that hosts Retail Server.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailServerAppPoolName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the application pool that the web application runs under.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailServerWebsiteName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the website that Retail Server runs on.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailServerAppPoolUsername</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that runs the application pool for Retail Server.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>RetailServerAppPoolPassword</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailServerAppPoolPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account that runs the application pool.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>RetailServerAppPoolUsername</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailServerSslCertThumbprint</em></p></td>
<td><p>None</p></td>
<td><p>Specify the thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailServerDatabase</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the channel database that is used with Retail Server.</p>
<p>You can connect to an existing channel database only. Setup doesn’t create a new channel database if you enter a channel database name that doesn’t exist.</p></td>
</tr>
<tr class="odd">
<td><p><em>RetailServerDatabaseServerName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the server that hosts the channel database.</p></td>
</tr>
<tr class="even">
<td><p><em>RetailServerDatabaseServerInstanceName</em></p></td>
<td><p>None</p></td>
<td><p>If needed, specify the name of the instance of SQL Server that hosts the channel database.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveRetailServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Server is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail Server.</p></li>
<li><p>1 – Remove Retail Server.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Store Connect parameters

The following table lists the parameters that control how Setup installs and removes Retail Store Connect.

These parameters apply only to Retail Store Connect in Microsoft Dynamics AX 2012 Feature Pack. In AX 2012 R3 and AX 2012 R2, Retail Store Connect is called Commerce Data Exchange: Synch Service, and the parameter names are different. For more information, see Commerce Data Exchange: Synch Service parameters.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailSC</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Store Connect is installed.</p>
<ul>
<li><p>0 – Don’t install Retail Store Connect.</p></li>
<li><p>1 – Install Retail Store Connect.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>UninstallRetailSC</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Store Connect is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail Store Connect.</p></li>
<li><p>1 – Remove Retail Store Connect.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Retail Transaction Service parameters

The following table lists the parameters that control how Setup installs and removes Retail Transaction Service.

These parameters apply only to Retail Transaction Service in Microsoft Dynamics AX 2012 Feature Pack. In AX 2012 R3 and AX 2012 R2, Retail Transaction Service is called Commerce Data Exchange: Real-time Service, and the parameter names are different. For more information, see Commerce Data Exchange: Real-time Service parameters.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallRetailTS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Transaction Service is installed.</p>
<ul>
<li><p>0 – Don’t install Retail Transaction Service.</p></li>
<li><p>1 – Install Retail Transaction Service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>UninstallRetailTS</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Retail Transaction Service is removed.</p>
<ul>
<li><p>0 – Don’t remove Retail Transaction Service.</p></li>
<li><p>1 – Remove Retail Transaction Service.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Synchronization service and synchronization proxy parameters

The following table lists the parameters that control how Setup installs and removes the synchronization service and synchronization proxy for Microsoft Project Server.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallSynchronizationService</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the synchronization service is installed.</p>
<ul>
<li><p>0 – Don’t install the synchronization service.</p></li>
<li><p>1 – Install the synchronization service, and create a new message queue.</p></li>
<li><p>2 – Install the synchronization service, and use an existing message queue.</p></li>
</ul>
<p>The synchronization service can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchronizationServiceMSMQAddress</em></p></td>
<td><p>None</p></td>
<td><p>Specify the address of the message queue that is used together with the synchronization service. This parameter is valid only if <em>InstallSynchronizationService</em>=2.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchronizationServiceMSMQType</em></p></td>
<td><p>0</p></td>
<td><p>Specify the type of message queue that is created.</p>
<ul>
<li><p>0 – Create a private queue.</p></li>
<li><p>1 – Create a public queue.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>SynchronizationServiceAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that the synchronization service runs as.</p>
<p>The synchronization service uses this account to connect to Microsoft Dynamics AX and to access the Project Server database.</p>
<p>Enter the account in the format <em>domain\account</em>.</p>
<p>This parameter is optional when you install the synchronization service, because Setup can retrieve the value from the database. The parameter is required when you install the synchronization proxy.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>SynchronizationServiceAccountPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchronizationServiceAccountPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account for the synchronization service.</p>
<p>If you use a standard domain account, this parameter is required if <em>InstallSynchronizationService</em> is set to 1 or 2.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchronizationServiceMsmqAccounts</em></p></td>
<td><p>None</p></td>
<td><p>Specify the accounts to which permissions for the message queues are granted. You must specify two types of accounts:</p>
<ul>
<li><p>The account that is used by the Project Server event service</p></li>
<li><p>The service accounts for all AOS instances that you want to use for synchronization</p></li>
</ul>
<p>Enter the value in the format <em>domain\account</em> or <em>account</em>. If you don’t specify a domain, the domain that the local computer belongs to is used. If you specify a local account, use the name of the local computer as the domain. For example, use <em>ComputerName\LocalAccount</em> or NT AUTHORITY\NETWORK SERVICE.</p>
<p>To include multiple service accounts, separate the values by using a semicolon (;).</p>
<div class="alert">

> [!NOTE]
> <P>The spelling of built-in accounts must match the spelling that is used by the language version of the operating system.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><em>InstallSynchronizationProxy</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether the synchronization proxy is installed.</p>
<ul>
<li><p>0 – Don’t install the synchronization proxy.</p></li>
<li><p>1 – Install the synchronization proxy.</p></li>
</ul>
<p>The synchronization proxy can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchronizationProxySqlServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the SQL Server instance that Project Server uses for reporting. This parameter is required if <em>InstallSynchronizationProxy</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>SynchronizationProxySqlDatabaseName</em></p></td>
<td><p>ProjectServer_Reporting, if the database exists on the SQL Server instance and <em>HideUI</em>=1. Otherwise, there is no default value.</p></td>
<td><p>Specify the SQL Server database that the Project Server uses for reporting. This parameter is required if <em>InstallSynchronizationProxy</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>SynchronizationProxyUrl</em></p></td>
<td><p>None</p></td>
<td><p>Specify the URL for Project Web access. This parameter is required if <em>InstallSynchronizationProxy</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveSynchronizationService</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an installed instance of the synchronization service is removed.</p>
<ul>
<li><p>0 – Don’t remove the synchronization service.</p></li>
<li><p>1 – Remove the synchronization service.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveSynchronizationProxy</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether an installed instance of the synchronization proxy is removed.</p>
<ul>
<li><p>0 – Don’t remove the synchronization proxy.</p></li>
<li><p>1 – Remove the synchronization proxy.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Trace Parser parameters

The following table lists the parameters that control how Setup installs and removes Trace Parser.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallTraceParser</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Trace Parser is installed.</p>
<ul>
<li><p>0 – Don’t install Trace Parser.</p></li>
<li><p>1 – Install Trace Parser.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>RemoveTraceParser</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Trace Parser is removed.</p>
<ul>
<li><p>0 – Don’t remove Trace Parser.</p></li>
<li><p>1 – Remove Trace Parser.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Visual Studio Tools parameters

The following table lists the parameters that control how Setup installs and removes the Visual Studio Tools.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallVisualStudioTools</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Visual Studio Tools are installed.</p>
<ul>
<li><p>0 – Don’t install Visual Studio Tools.</p></li>
<li><p>1 – Install Visual Studio Tools.</p></li>
</ul>
<p>If <em>InstallVisualStudioTools</em>=1, you must also specify a value for <em>ClientAosServer</em>, <em>AosPort</em>, and <em>AosWsdlPort</em>. You can optionally specify a value for <em>AosInstance</em>.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveVisualStudioTools</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Visual Studio Tools are removed.</p>
<ul>
<li><p>0 – Don’t remove Visual Studio Tools.</p></li>
<li><p>1 – Remove Visual Studio Tools.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## VSS writer parameters

The following table lists the parameters that control how Setup installs and removes VSS writer.


> [!NOTE]
> <P>The VSS writer is available through Setup only in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallVss</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether VSS writer is installed.</p>
<ul>
<li><p>0 – Don’t install VSS writer.</p></li>
<li><p>1 – Install VSS writer.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>DpmServer</em></p></td>
<td><p>None</p></td>
<td><p>Specify the server where System Center Data Protection Manager (DPM) is installed.</p></td>
</tr>
<tr class="odd">
<td><p><em>TempBackupPath</em></p></td>
<td><p>None</p></td>
<td><p>Specify the location where temporary backups will be stored.</p></td>
</tr>
<tr class="even">
<td><p><em>VssServiceAccount</em></p></td>
<td><p>None</p></td>
<td><p>Specify the account that the Windows service for the VSS writer runs as.</p>
<p>If you specify an account, the value must be in the format <em>domain\account</em>. The account must be a domain account. You can’t specify your own account or a local computer account.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>VssServicePassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>VssServicePassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the VSS writer service account.</p>
<p>If you use a standard domain account, you must specify a value for this parameter if you specify a value for the <em>VssServiceAccount</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>ProtectAos</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether to protect an AOS instance with VSS writer.</p>
<ul>
<li><p>0 – Don’t protect an AOS instance.</p></li>
<li><p>1 – Protect an AOS instance.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>VssAosInstanceNumber</em></p></td>
<td><p>None</p></td>
<td><p>Specify the instance number of the AOS instance to protect.</p>
<p>This parameter is required if <em>ProtectAos</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>ProtectSsas</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether to protect an instance of Analysis Services with VSS writer.</p>
<ul>
<li><p>0 – Don’t protect an instance of Analysis Services.</p></li>
<li><p>1 – Protect an instance of Analysis Services.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>VssAnalysisInstance</em></p></td>
<td><p>None</p></td>
<td><p>Specify the instance of Analysis Services to protect.</p>
<p>This parameter is required if <em>ProtectSsas</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>ProtectSsrs</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether to protect an instance of Reporting Services with VSS writer.</p>
<ul>
<li><p>0 – Don’t protect an instance of Reporting Services.</p></li>
<li><p>1 – Protect an instance of Reporting Services.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><em>VssReportingDbName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the reporting database to protect.</p></td>
</tr>
<tr class="even">
<td><p><em>VssReportingInstance</em></p></td>
<td><p>None</p></td>
<td><p>Specify the instance of Reporting Services to protect.</p>
<p>This parameter is required if <em>ProtectSsrs</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>VssReportingInstanceRemote</em></p></td>
<td><p>None</p></td>
<td><p>Specify the SQL Server instance that hosts the Reporting Services database.</p>
<p>This parameter is required if <em>ProtectSsrs</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>VssReportingMachine</em></p></td>
<td><p>None</p></td>
<td><p>Specify the computer that hosts the Reporting Services database.</p>
<p>This parameter is required if <em>ProtectSsrs</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>ProtectDb</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether to protect the Microsoft Dynamics AX database by using VSS writer.</p>
<ul>
<li><p>0 – Don’t protect the Microsoft Dynamics AX database.</p></li>
<li><p>1 – Protect the Microsoft Dynamics AX database.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>VssDbName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the Microsoft Dynamics AX database to protect.</p>
<p>This parameter is required only if <em>ProtectDb</em>=1.</p></td>
</tr>
<tr class="odd">
<td><p><em>VssDbInstance</em></p></td>
<td><p>None</p></td>
<td><p>Specify the SQL Server instance that hosts the Microsoft Dynamics AX database.</p>
<p>This parameter is required only if <em>ProtectDb</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>RemoveVss</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether VSS writer is removed.</p>
<ul>
<li><p>0 – Don’t remove VSS writer.</p></li>
<li><p>1 – Remove VSS writer.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Warehouse Mobile Devices Portal parameters

The following table lists the parameters that control how Setup installs and removes the Warehouse Mobile Devices Portal.


> [!NOTE]
> <P>Warehouse Mobile Devices Portal is available through Setup only in AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallWarehouseServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Warehouse Mobile Devices Portal is installed.</p>
<ul>
<li><p>0 – Don’t install Warehouse Mobile Devices Portal.</p></li>
<li><p>1 – Install Warehouse Mobile Devices Portal.</p></li>
</ul>
<p>If <em>InstallWarehouseServer</em>=1, you must also include the parameter <em>AcceptBestPracticesList</em>=1.</p></td>
</tr>
<tr class="even">
<td><p><em>WarehouseAccount</em></p></td>
<td><p>None</p></td>
<td><p>Optionally, use this parameter instead of the <em>WarehouseUserDomain</em> and <em>WarehouseUserName</em> parameters.</p>
<p>Enter the value in the format <em>Domain\account</em>.</p></td>
</tr>
<tr class="odd">
<td><p><em>WarehouseUserName</em></p></td>
<td><p>None</p></td>
<td><p>Specify the name of the user that runs the application pool for Warehouse Mobile Devices Portal.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>WarehouseUserDomain</em> parameter and the <em>WarehouseUserPassword</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>WarehouseUserDomain</em></p></td>
<td><p>None</p></td>
<td><p>Specify the domain of the user that runs the application pool for Warehouse Mobile Devices Portal.</p>
<p>If you specify a value for this parameter, you must also specify a value for the <em>WarehouseUserName</em> parameter and the <em>WarehouseUserPassword</em> parameter.</p></td>
</tr>
<tr class="odd">
<td><p><em>WarehouseUserPassword</em></p></td>
<td><p>None</p></td>
<td><p>Specify the password that is associated with the account that runs the application pool.</p>
<p>You must specify a value for this parameter if you specify a value for the <em>WarehouseUserName</em> parameter.</p></td>
</tr>
<tr class="even">
<td><p><em>WarehouseSitePort</em></p></td>
<td><p>None</p></td>
<td><p>Enter the port number that the website will run on.</p></td>
</tr>
<tr class="odd">
<td><p><em>RemoveWarehouseServer</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether Warehouse Mobile Devices Portal is removed.</p>
<ul>
<li><p>0 – Don’t remove Warehouse Mobile Devices Portal.</p></li>
<li><p>1 – Remove Warehouse Mobile Devices Portal.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><em>WarehouseInstanceNumber</em></p></td>
<td><p>None</p></td>
<td><p>Specify the number of the Warehouse Mobile Devices Portal instance to remove.</p>
<p>Specify a value for this parameter only when you uninstall Warehouse Mobile Devices Portal.</p></td>
</tr>
</tbody>
</table>


## Web services on IIS parameters

The following table lists the parameters that control how Setup installs and removes web services on Internet Information Services (IIS).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>InstallAifWebServices</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether web services are installed on IIS.</p>
<ul>
<li><p>0 – Don’t install web services on IIS.</p></li>
<li><p>1 – Install web services on IIS.</p></li>
</ul>
<p>Web services on IIS can be installed only one time.</p></td>
</tr>
<tr class="even">
<td><p><em>AifWebServicesWebSite</em></p></td>
<td><p>None</p></td>
<td><p>Specify the website where Setup creates the virtual directory for web services on IIS.</p></td>
</tr>
<tr class="odd">
<td><p><em>AifWebServicesApplicationPool</em></p></td>
<td><p>MicrosoftDynamicsAXAif60</p></td>
<td><p>Specify the name of the application pool that is created. The name can’t include the following characters: asterisks (*), backslashes (\), pipes (|), question marks (?), or slashes (/).</p></td>
</tr>
<tr class="even">
<td><p><em>AifWebServicesVirtualDirectory</em></p></td>
<td><p>MicrosoftDynamicsAXAif60</p></td>
<td><p>Specify the name of the virtual directory that is created. The name can’t include the following characters: asterisks (*), backslashes (\), pipes (|), question marks (?), or slashes (/).</p></td>
</tr>
<tr class="odd">
<td><p><em>AifWebServicesAosAccounts</em></p></td>
<td><p>See the description.</p></td>
<td><p>Specify the AOS service accounts that are added to the shared directory. If an AOS instance is already installed on this computer, the default account is the service account of the AOS instance that was most recently installed.</p>
<p>Enter the value in the format <em>Domain\account</em> or <em>account</em>. If you don’t specify a domain, the domain that the local computer belongs to is used. If you specify a local account, use the name of the local computer as the domain. For example, use <em>ComputerName\LocalAccount</em> or NT AUTHORITY\NETWORK SERVICE.</p>
<p>To include multiple service accounts, separate the values by using a semicolon (;).</p>
<div class="alert">

> [!NOTE]
> <P>The spelling of built-in accounts must match the spelling that is used by the language version of the operating system.</P>


</div></td>
</tr>
<tr class="even">
<td><p><em>RemoveAifWebServices</em></p></td>
<td><p>0</p></td>
<td><p>Specify whether web services on IIS are removed.</p>
<ul>
<li><p>0 – Don’t remove web services on IIS.</p></li>
<li><p>1 – Remove web services on IIS.</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

