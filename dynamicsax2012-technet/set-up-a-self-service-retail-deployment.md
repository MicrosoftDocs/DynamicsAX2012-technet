---
title: Set up a self-service Retail deployment
TOCTitle: Set up a self-service Retail deployment
ms:assetid: fd6b63ac-0aa0-4fd3-80c5-48a01590df08
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn858399(v=AX.60)
ms:contentKeyID: 63417193
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up a self-service Retail deployment 


This topic describes how the system administrator uses the Retail mass deployment toolkit to prepare a self-service installation of Retail components.

In a self-service installation, the user at the store installs the Retail software at the store. The user doesn’t need knowledge of the IT infrastructure to complete the installation. The system administrator at headquarters creates an installation package that contains all the information that is needed for installation, and the user runs it.


> [!NOTE]
> <P>Self-service installation is available starting with Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



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
<td><p>Install the toolkit</p></td>
<td><p><a href="install-the-retail-mass-deployment-toolkit.md">Install the Retail mass deployment toolkit</a></p>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Dn527205.alert_note(AX.60).gif" title="Tip" alt="Tip" class="note" /><strong>Tip</strong>
</div>
<div class="mtps-row">
To see the full list of commands that are available for the toolkit, open a Command Prompt window in the folder where RetailConfigMgrToolkit.exe is installed, and type <strong>RetailConfigMgrToolkit.exe</strong>. To see the parameters that are available for a command, run the command <strong>RetailConfigMgrToolkit.exe -o &lt;command&gt; -?</strong>.
</div>
</div>
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
</tbody>
</table>


## Set the path to the deployment tools

Before you create an installation package, you must specify where the mass deployment toolkit is installed.

1.  Open the Retail shared parameters form. (Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.)

2.  Click the **Deployment** tab.

3.  Specify the path where the Retail mass deployment toolkit is installed. By default, the toolkit is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\.
    
    The path that you specify in this form is used only in self-service deployments. It is not used by other mass deployment scenarios.

## Import the deployment plan

After computers and deployment information have been defined in Microsoft Dynamics AX, you can import the deployment plan into the self-service installer by using the Retail mass-deployment toolkit.

1.  Copy the deployment .xml file to the computer. For information about how to create the .xml file, see [Set up a Retail topology to use with deployment tools](set-up-a-retail-topology-to-use-with-deployment-tools.md).

2.  Open a Command Prompt window, and change the directory to the folder where RetailConfigMgrToolkit.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerToolKit.

3.  Run the following command to import the file:
    
    **RetailConfigMgrToolkit.exe -o -ImportRetailTopology -f \<file name\>**
    
    The deployment package contains the following files:
    
      - Prerequisite checker
    
      - Installer (.msi) files for each component that is being installed
    
      - Support files that are required for installation
    
      - Topology.xml
    
      - Setup.exe

## Make packages available to users

The user who will run the installation package must be an administrator on the local computer. To access the Enterprise Portal page, he must belong to the Retail self-service deployment security role.

Set up Enterprise Portal to host packages. Make sure to update Enterprise Portal to CU8.

Send emails. Provide the following information to users:

  - URL to the Enterprise Portal page

  - Password to create the installation package

The user goes to each computer in the store and accesses the Enterprise Portal page. The page detects the local computer, and asks the user to resolve any conflicts with machine names. The user can reset the password if necessary. When the user clicks **Download**, an installation package is created for that computer. The user opens the .zip file and runs Setup.exe. They’ll see a progress bar, but won’t need to enter any additional information.

  


