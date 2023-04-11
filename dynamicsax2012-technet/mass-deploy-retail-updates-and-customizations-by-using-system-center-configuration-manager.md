---
title: Mass deploy retail updates and customizations by using System Center Configuration Manager
TOCTitle: Mass deploy retail updates and customizations by using System Center Configuration Manager
ms:assetid: 188cd18c-6dbf-4ed4-b359-af5386e1a370
ms:mtpsurl: https://technet.microsoft.com/library/Dn858396(v=AX.60)
ms:contentKeyID: 63417189
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Mass deploy retail updates and customizations by using System Center Configuration Manager 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the Retail Update generator with System Center Updates Publisher to automate and centralize the deployment of customizations and updates to the retail components of Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>Mass deployment of customizations is supported only for the Retail POS and Retail Channel Configuration Utility.</P>



The Update generator is part of the Retail mass deployment toolkit, which is a command-line tool that you can use to automate and centralize the deployment of the retail components of Microsoft Dynamics AX.

System Center Updates Publisher enables you to import software updates from external catalogs, create and modify update definitions, export updates to external catalogs, and publish updates to a configured update server. When you use Updates Publisher to manage updates and publish them to the update server, administrators can detect and deploy published updates to client and server computers by using System Center Configuration Manager. For more information about Updates Publisher, see the [System Center Updates Publisher documentation](https://technet.microsoft.com/library/hh134742.aspx).

This topic includes the following information:

  - Prerequisites

  - Mass deploy software updates for retail components

  - Mass deploy customizations for retail components

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
To see the full list of commands that are available for the Update generator, open a Command Prompt window in the folder where UpdateGenerator.exe is installed, and type <strong>UpdateGenerator.exe -?</strong>. To see the parameters that are available for a command, run the command <strong>UpdateGenerator.exe -? -o &lt;command&gt; -?</strong>.
</div>
</div>
</div></td>
</tr>
<tr class="even">
<td><p>Install System Center Updates Publisher 2011</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=511859">System Center Updates Publisher</a></p></td>
</tr>
</tbody>
</table>


## Mass deploy software updates for retail components

Use the following procedure to mass deploy updates to Retail components. For more information about how to apply hotfixes and updates to Retail components, see [Deploy updates in a retail environment](deploy-updates-in-a-retail-environment.md).

1.  To find updates, go to [Microsoft Dynamics Lifecycle Services](https://lcs.dynamics.com), select a project, and then click **Updates**. In the **Updates to include with new installations** section, select the update package that you want, and download it.

2.  Open a Command Prompt window and change the directory to the folder where UpdateGenerator.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\UpdateGenerator.

3.  Run the following command to generate a catalog file that contains metadata from the update package (.msp):
    
    UpdateGenerator.exe \<Path to .msp file\> -o \<outputfile.cab\>

4.  Start System Center Updates Publisher.

5.  Import the generated catalog file into Updates Publisher and create an update package.
    

    > [!NOTE]
    > <P>For information about how to use Updates Publisher, see the <A href="https://go.microsoft.com/fwlink/?linkid=511873">series of videos</A> on TechNet.</P>



6.  Publish the software updates package to System Center Configuration Manager.

7.  From System Center Configuration Manager, deploy the software updates to a target collection. If you are updating the Retail Channel Configuration Utility, also run the **Configure Retail Channel database** task sequence to run the utility after it has been patched.

## Mass deploy customizations for retail components

Use the following procedure to deploy customizations to Retail components. Mass deployment of customizations is supported only for Retail POS and Retail Channel Configuration Utility.


> [!NOTE]
> <P>Retail SDK and Visual Studio must be installed to complete this procedure. For information about how to install Retail SDK, see <A href="install-retail-sdk-retail-pos-plug-ins.md">Install Retail SDK (Retail POS Plug-ins)</A>.</P>



1.  Create the customization. For more information about how to customize Retail POS, see [Extend Point of Sale](extend-point-of-sale.md).

2.  Start Visual Studio.

3.  Open the following project: My Documents \> Retail SDK \> Scaleout Deployment \> CustomizationDeployment \> CustomizationDeployment.csproj.

4.  Open the CustomizationDeployment.xml file.

5.  Enter values for **patchName** and **company**.

6.  List the source files that are needed for the customization.

7.  If you are customizing Retail Channel Configuration Utility, provide the path where the utility is installed. The default installation path is provided as an example in the file.

8.  Include the customizations in the **Files** folder in your project.

9.  Build the project. The binary .exe file will be used to generate a software update in Updates Publisher.

10. Open a Command Prompt window and change the directory to the folder where UpdateGenerator.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\UpdateGenerator.

11. Run the following command to generate a catalog file:
    
    UpdateGenerator.exe \<Path to .exe file\> -o \<outputfile.cab\>

12. Start System Center Updates Publisher.

13. Import the catalog file into Updates Publisher and create an update package.
    

    > [!NOTE]
    > <P>For information about how to use Updates Publisher, see the <A href="https://go.microsoft.com/fwlink/?linkid=511873">series of videos</A> on TechNet.</P>

    
    Use the following information where applicable.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>POS Product ID</p></td>
    <td><p>C29E75E5-D606-40A6-A619-9F7C45067952</p></td>
    </tr>
    <tr class="even">
    <td><p>Channel Configuration Utility (Database Utility) Product ID</p></td>
    <td><p>AEDE45DD-25BA-48ED-8FC5-FD08B6747545</p></td>
    </tr>
    <tr class="odd">
    <td><p>Registry key</p></td>
    <td><p>HKLM &gt; SOFTWARE &gt; <em>CompanyName</em> &gt; <em>CustomizationName</em> &gt; <em>ComponentName</em>, where the component name is either “Retail POS” or “Retail Database Utility”</p></td>
    </tr>
    </tbody>
    </table>


14. Publish the software update package to System Center Configuration Manager.

15. From System Center Configuration Manager, deploy the update package to a target collection. If you customized the Retail Channel Configuration Utility, run the **Configure Retail Channel database** task sequence to run the utility after it has been patched.

  


