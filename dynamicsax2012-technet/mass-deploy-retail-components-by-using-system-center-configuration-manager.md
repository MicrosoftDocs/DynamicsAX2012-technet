---
title: Mass deploy Retail components by using System Center Configuration Manager
TOCTitle: Mass deploy Retail components by using System Center Configuration Manager
ms:assetid: 15ded62a-f6d3-44a4-8fe6-93e7f19ea558
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497719(v=AX.60)
ms:contentKeyID: 62200200
ms.date: 10/28/2016
mtps_version: v=AX.60
---

# Mass deploy Retail components by using System Center Configuration Manager 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>



Use the Retail mass deployment toolkit with System Center Configuration Manager to automate and centralize the deployment of the retail components of Microsoft Dynamics AX.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2.</P>



The Retail mass deployment toolkit is a command-line tool that you can use to facilitate mass deployment of the retail components of Microsoft Dynamics AX.

Configuration Manager enables secure and scalable software deployment, management of compliance settings, and comprehensive asset management for servers, desktops, portable computers, and mobile devices. For more information about Configuration Manager, see the [System Center Configuration Manager TechCenter](http://technet.microsoft.com/en-us/systemcenter/hh285244) on TechNet.

This topic includes the following information:

  - Prerequisites

  - Bootstrap Configuration Manager with the Dynamics Retail installer

  - Import the retail deployment plan into System Center

  - Deploy retail components by using System Center

## Prerequisites

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify permissions on the system, and prepare to install</p></td>
<td><p>Ensure that no more than one user is logged on during installation. If more than one user is logged on, task sequences may not show up correctly.</p>
<p>The NT\Local System must be an admin on the SQL Server where any of the databases are being deployed (Retail Channel Database, Offline Database, Async Server Message Database, Async Client Message Database).</p>
<p>The provisioning user must be a local administrator and a SQL Server administrator.</p>
<p>SQL Server ports must be enabled.</p>
<p>Remote management ports must be enabled.</p>
<p>The POS account specified in the POS deployment form in Microsoft Dynamics AX must be a local administrator on the POS computer.</p></td>
</tr>
<tr class="even">
<td><p>Verify permissions in System Center</p></td>
<td><p>In order to deploy components you must be a member of either the Full Administrator or Operations Administrator role in System Center.</p></td>
</tr>
<tr class="odd">
<td><p>Install the toolkit</p></td>
<td><p><a href="install-the-retail-mass-deployment-toolkit.md">Install the Retail mass deployment toolkit</a></p>
<div>

> [!TIP]
> <P>To see the full list of commands that are available for the toolkit, open a Command Prompt window in the folder where RetailConfigMgrToolkit.exe is installed, and type <STRONG>RetailConfigMgrToolkit.exe</STRONG>. To see the parameters that are available for a command, run the command <STRONG>RetailConfigMgrToolkit.exe -o &lt;command&gt; -?</STRONG>.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Define the topology</p></td>
<td><p><a href="set-up-a-retail-topology-to-use-with-deployment-tools.md">Set up a Retail topology to use with deployment tools</a></p></td>
</tr>
<tr class="odd">
<td><p>Create security files</p></td>
<td><p><a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a></p></td>
</tr>
<tr class="even">
<td><p>Set up a location for log files</p></td>
<td><p>Specify a location for Retail deployment logs</p></td>
</tr>
<tr class="odd">
<td><p>Discover computers in System Center Configuration Manager</p></td>
<td><p>Any computer entities for Microsoft Dynamics AX must already be discovered by Configuration Manager before you import the topology to Configuration Manager. For more information, see <a href="https://technet.microsoft.com/en-us/library/gg712308.aspx">Planning for Discovery in Configuration Manager</a>.</p>
<p>Workgroup computers must be approved in Configuration Manager before you can deploy components to them.</p>
<p>You must manually create Async Server working folders when installing Async Server via mass-deployment. These folders will not be created by the mass deployment process.</p></td>
</tr>
</tbody>
</table>


## Bootstrap Configuration Manager with the Dynamics Retail installer

Before you can use Configuration Manager with Retail mass deployment, you must first bootstrap Configuration Manager with Dynamics Retail installer. To do this, you must run the following command in the Retail mass deployment toolkit:

     
    RetailConfigMgrToolkit.exe -o CreateRetailApplications –contentRoot <UNC path of the shared folder where retail application files are located> 

 This path can be obtained by sharing the following folder: C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerContent.

## Import the retail deployment plan into Configuration Manager

After computers and deployment information have been defined in Microsoft Dynamics AX, you can export the deployment plan and import it into Configuration Manager.

1.  Copy the deployment XML file to the computer that is running the Configuration Manager console. For information about how to create the XML file, see [Set up a Retail topology to use with deployment tools](set-up-a-retail-topology-to-use-with-deployment-tools.md).

2.  Open a Command Prompt window, and change the directory to the folder where RetailConfigMgrToolkit.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerToolKit.

3.  Run the following command to import the file:
    
    **RetailConfigMgrToolkit.exe -o ImportRetailTopology -f \<file name\>**
    
    By default, the file is imported to the Retail root collection. To specify a different collection, run the command **–targetCollection \<unique name for the topology\>**.

## Deploy retail components by using Configuration Manager

1.  
    

    > [!NOTE]
    > <P>This step is required if you are running AX 2012 R3. It is not required if you are running AX 2012 R3 CU8</P>

    
    Create a shared folder where deployment logs will be saved. Make sure that the administrator who manages deployments has access to the folder. In addition, Configuration Manager clients must have access to upload deployment logs to the shared folder.

2.  
    

    > [!NOTE]
    > <P>This step is required if you are running AX 2012 R3. It is not required if you are running AX 2012 R3 CU8</P>

    
    On the computer where the Configuration Manager console is installed, run the toolkit to set the log share for a target collection. Run the following command:
    
    **RetailConfigMgrToolkit.exe -o SetRetailLogShare -LogShare \<UNC path of shared folder\> LogShareAccount \<Account to access the share\> LogSharePassword \<Password for the account\> targetCollection \<targetCollection name\>**

3.  Install prerequisites on the target computers. You can create applications, packages, or task sequences in Configuration Manager to deploy prerequisites.
    

    > [!IMPORTANT]
    > <P>On computers where channel, offline, or message databases will be created, the built-in <STRONG>LocalSystem</STRONG> account must belong to the <STRONG>sysadmin</STRONG> server role in SQL Server.</P>



4.  Distribute content for the task sequences to the desired distribution point. The Retail installation files can be deployed only if they are copied to the distribution point.

5.  
    

    > [!NOTE]
    > <P>This step is required if you are running AX 2012 R3. It is not required if you are running AX 2012 R3 CU8</P>

    
    Set up user accounts for Retail components. User names and passwords must be set up for the following components:
    
      - Real-time Service application pool
    
      - Retail Server application pool
    
      - Async Server application pool
    
      - Async Client (Windows service)
    
      - Async Client data store
    
      - Offline sync service
    
      - Channel database for Retail POS
    
    For example, run the following command to set user accounts and passwords for Real-time Service and Retail Server:
    
    **RetailConfigMgrToolkit.exe -o SetCredentials -collection \<target collection\> -rtsaccount \<AccountName\> -rtspassword \<Password\> -retailserveraccount \<AccountName\> -retailserverpassword \<Password\>**
    

    > [!TIP]
    > <P>To see the full list of parameters for accounts and passwords, run the command <STRONG>RetailConfigMgrToolkit.exe –o SetCredentials /?</STRONG>.</P>



6.  In Configuration Manager, schedule a deployment for the following task sequences for the target collection of the Retail topology. You can find these tasks in the Configuration Manager console, under **Software Library** \> **Operation Systems** \> **Task Sequences**.
    

    > [!NOTE]
    > <P>When you run a task sequence, only one user must be logged on to the computer.</P>

    
      - Retail Role Manager
        

        > [!NOTE]
        > <P>You must deploy this task sequence first.</P>

    
      - Update group membership
    
      - Install and configure Retail components
    
      - Uninstall Retail components
    
      - Collect Retail Logs
    
      - Configure offline database

7.  In Configuration Manager, schedule a deployment for the Retail Modern POS application.
    

    > [!NOTE]
    > <P>Only the Retail Modern POS application can be run directly. Do not deploy any other Configuration Manager applications or packages directly.</P>



8.  You can deploy offline databases after Async Server, Async Client, and the channel database have been deployed.
    
    Before you deploy offline databases, on the computer that hosts the channel database, use SQL Server Management Studio to assign the local **OfflineSyncServiceUsers** group to the **sysadmin** server role in SQL Server. Alternatively, you can assign the **OfflineSyncServiceUsers** group to the dbo schema in SQL Server.
    
    To synchronize data between Microsoft Dynamics AX and the channel database, in Microsoft Dynamics AX, run all distribution schedules. (Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**. Select a distribution schedule, and then click **Run now**.)
    
    After the distribution schedule has finished running, and data has been sent to the channel database, the “Configure offline database” task sequence provisions offline databases and triggers the synchronization between the channel database and offline databases.

## Known issues and workarounds

**Issue** When you upgrade from AX 2012 R3 to AX 2012 R3 cumulative update 8, and launch the mass-deployment forms, you will see a "Name is required" error message.

**Resolution** Type and erase a character in the name field.

**Issue** The Export retail topology toolkit command cannot filter by multiple stores (For example, -s HOUSTON, BOSTON finds only Houston).

**Resolution** No known workaround.

**Issue** If Retail Modern POS offline configuration fails because of disconnected drives on the computer when powershell is launched, you may see an error message that says 'failed to initialize default drives'.  

**Resolution** Make the following modifications to the scripts in the ConfigureRetail component folder in the Install directory of the Retail Mass Deployment Toolkit. In the Configure-RetailModernPosOffline.psm1 fileAdd   -ErrorAction 'Continue' to the end of the following line:

    $configureOfflineExitCode = Invoke-CommandLineExpressionAndGetExitCode -commandLineExpression $configureOfflineCommand -logFile $logFile

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

