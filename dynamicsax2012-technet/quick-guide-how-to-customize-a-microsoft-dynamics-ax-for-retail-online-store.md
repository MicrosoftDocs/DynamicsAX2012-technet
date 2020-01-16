---
title: 'Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store'
TOCTitle: 'Quick Guide: How to customize an online store'
ms:assetid: bf349222-f278-446f-bc27-e2fb2bf53ba0
ms:mtpsurl: https://technet.microsoft.com/library/Dn387566(v=AX.60)
ms:contentKeyID: 58487399
author: Khairunj
ms.date: 07/29/2015
mtps_version: v=AX.60
---

# Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to customize the online store by using SharePoint features and the Visual Studio source-code projects that are included in the Retail SDK. This topic also describes how to deploy customizations in development, test, and production environments. For information about developer prerequisites, including Microsoft Visual Studio, see [Set up the development environment for SharePoint 2013](https://go.microsoft.com/fwlink/?linkid=299477).

## Before you begin

**Use SharePoint features to change the look and feel of the application**

SharePoint enables you to customize the user interface of the application. Developers and administrators can edit master pages, change styles, add new pages, and change web part properties, to name a few options. You can perform these tasks in SharePoint or with 3rd party development tools that access SharePoint. It is recommended to use these tools for the initial customization process. For information about modifying web parts, including the Content Search Web Parts that display products in the store, see [Edit existing Web Parts in SharePoint 2013](https://go.microsoft.com/fwlink/?linkid=395066%26clcid=0x409).

**Use the SDK to change the behavior, look, and feel of the application**

The Retail SDK includes the source code of many retail online store features. By examining the source code, you can understand the application and adapt it to meet your needs. For example, you can implement shipping-provider calculations in the [Commerce Runtime](commerce-runtime.md), add support for a new identity provider, or add more business-related logging to understand what online users are doing at certain stages of the checkout process. All of these changes require you to change source code. The following information describes how to customize the Retail online store by using the Retail SDK and then deploy those changes in different environments.

## Install developer tools and features

You must install the Retail SDK, the Retail Online Channel, and the latest Microsoft Dynamics AX 2012 R2 cumulative updates on the SharePoint server before you can customize the Retail online store. If you deployed the Retail online store as described in [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md), then you have already installed the Retail Online Channel and the latest cumulative update. Use the following procedure to verify that the server has the required tools, features, and updates for customizing the Retail online store.

1.  On the SharePoint server locate the following directories:
    
    C:\\My Documents\\Retail SDK
    
    \-and-
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel

2.  If you do not see these folders, then you must install the Retail SDK and the Retail Online Channel by using Microsoft Dynamics AX Setup.exe. For more information, see [Install retail components](install-retail-components.md).

3.  If you have not done so, download and install the latest cumulative update for Microsoft Dynamics AX 2012 R2.

## Prepare your developer environment for signing updated source code

The process of customizing the Retail online store requires that you recompile the source code in the Visual Studio projects. After you recompile, the fully-qualified name of the rebuilt assemblies will be different than the assemblies originally provide by Microsoft. Before you can recompile the assemblies, you must provide a code signing key file (also called a strong name key file) to sign the customized code. If your business has a code signing key file (.snk file), you can reuse this file. If you do not have a code signing key file, Visual Studio can create one for you. You must create a new project and enable code signing. Then, create a second project that references the .dll of the output of the first project. You can locate the thumbprint in the assembly reference of the .csproj file in the second project. Once you have the .snk file, you must do the following:

1.  Save the file in the Retail SDK folder and give it a name *Name*.snk.

2.  Edit the UpdateAssemblyIdentities.ps1 file in the Retail SDK folder. You must update the version number and the thumbprint of the key file (lines 97, 98).

3.  Update the source code to use the strong name certificate by executing the UpdateAssemblyIdentities.ps1 script. This script can take several minutes to complete.

## Use Visual Studio 2012 to customize the Retail Online Store source code projects

Customization of the Retail online sample stores requires Microsoft Office Developer Tools for Visual Studio. Use the following steps to install the tools.

To download the Microsoft Web Platform Installer, see [Microsoft Web Platform Installer](https://go.microsoft.com/fwlink/?linkid=395063%26clcid=0x409).

### To install Microsoft Office Developer Tools for Visual Studio

1.  Open the Web Platform Installer, type **SharePoint** in the search box, and then press **Enter**.

2.  Select **Microsoft Office Developer Tools for Visual Studio 2012**.

3.  Click **Add** and then click **Install**.

The Retail SDK includes the following Visual Studio solution files before AX2012 R3 CU8:

  - **Services.sln**: Use this file to customize source code for the Commerce Run-time. The file is located in the Retail SDK\\Commerce Run-Time\\Services directory.

  - **StoreFront.sln**: Use this file to customize source code for the Retail online store. The file is located in the Retail SDK\\Online Channel\\StoreFront directory.

For AX 2012 R3 CU8, the Retail SDK is separated into 2 specific folders:

  - **Framework**: The framework consists of the core E-Commerce platform components for Publishing and Checkout Services. This primarily consists of a core library Publishing and E-Commerce Controllers) and services folder. It also contains the reusable checkout controls

  - **Clients**: There are 2 clients available in CU8. One is the SharePoint online store and the other a simple ASP.net online store. Both the clients use the Framework described above. To use the SharePoint online store, use SharePoint.Storefront.sln.

A typical development scenario might proceed as follows:

1.  The developer opens the **Services.sln** project in Visual Studio, clicks **Clean All**, customizes the solution, and then clicks **Build All**.
    
    Visual Studio creates the output assembly files in the Retail SDK\\Commerce Run-time\\References directory.

2.  The developer opens **StoreFront.sln**, project in Visual Studio, clicks **Clean All**, customizes the solution, and then clicks **Build All**.
    
    Visual Studio creates the output assembly files in the Retail SDK\\Online Channel\\References directory.

3.  In Visual Studio, the developer right-clicks the **StoreFront** project node in the **StoreFront** solution, and then clicks **Publish**. By default, Visual Studio publishes the updated solution to the C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\StoreFront\\ORIGINAL\_WSP directory. If this directory does not exist in your development environment, then you must create it.
    
    The publish process creates a new deployment package which you can deploy in a test environment to verify your changes.

## Deploy customizations in a test environment and verify your changes

Use the following procedure to deploy the Retail online store .wsp package you just created in a test environment to verify your customizations.

1.  Open the C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools\\**oob-topology.xml** file in Microsoft Visual Studio or a text editor, such as Notepad.

2.  Search in the oob-topology.xml file for the parameters listed in the following table. Enter the specified value for each parameter.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Search for</p></th>
    <th><p>Verify or change with</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>&lt;WSPPackage generate=&quot;true&quot; deploy=&quot;true&quot; retract=&quot;true&quot;&gt;</strong> <strong>&lt;InputFolder&gt;..\</strong> <em>RetailJobs</em> <strong>\SP&lt;/InputFolder&gt;</strong></p></td>
    <td><p>Verify that &lt;WSPPackage generate=&quot;true&quot;</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>&lt;WSPPackage generate=&quot;true&quot; deploy=&quot;true&quot; retract=&quot;true&quot;&gt;</strong> <strong>&lt;InputFolder&gt;..\Contoso</strong> <em>DemoData</em> <strong>\SP&lt;/InputFolder&gt;</strong></p></td>
    <td><p>Verify that &lt;WSPPackage generate=&quot;true&quot;</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>&lt;WSPPackage generate=&quot;true&quot; deploy=&quot;true&quot; retract=&quot;true&quot;&gt;</strong> <strong>&lt;InputFolder&gt;..\</strong> <em>StoreFront</em> <strong>\SP&lt;/InputFolder&gt;</strong></p></td>
    <td><p>Change &lt;WSPPackage generate=&quot;true&quot; to “false”</p></td>
    </tr>
    </tbody>
    </table>


3.  From a command prompt, open the directory where the oob-topology file is stored. By default, it is stored here:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools

4.  Execute the following command:
    
    powershell .\\Generate-WSP.ps1 oob-topology.xml oob-settings.xml

5.  After the PowerShell command is finished, update the oob-topology.xml file so that the RetailJobs and DemoData XML nodes specify **generate=false** and the StoreFront XML node specifies **generate=true**.

6.  Execute the following command:
    
    powershell .\\Prepare-FromWSP.ps1 oob-topology.xml oob-settings.xml

7.  After the PowerShell command is finished, execute the following command:
    
    powershell .\\InstallPrereqs-SPFarm.ps1 oob-topology.xml oob-settings.xml

8.  After the PowerShell command is finished, execute the following command:
    
    powershell .\\Deploy-FarmSolutions.ps1 oob-topology.xml oob-settings.xml

9.  Save your changes in the oob-topology.xml file.

10. Verify all of your changes. For more information, see “Verify deployment” in [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).

## Deploy your solution to a production environment

To deploy a customized Retail online store into a production environment, you must complete the processes described in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Process</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify that the Retail online channel has been installed and configured in Microsoft Dynamics AX</p></td>
<td><p>Setup procedures are listed in the <a href="online-store.md">Online Store</a> under the heading <strong>Setup and configure an online store</strong>. The topics in the roadmap supplement the online store setup checklist. The checklist is available in the Microsoft Dynamics AX client: <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Online store setup checklist</strong>. Use the procedures listed in the documentation roadmap and the checklist to finish setting up and configuring the Retail online channel.</p></td>
</tr>
<tr class="even">
<td><p>Copy the deployment packages and all associated files to the Web server farm</p></td>
<td><p>After you have verified your customized Retail online store, you can copy the C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel directory to the Web server farm.</p></td>
</tr>
<tr class="odd">
<td><p>Update the oob-topology.xml file for the production environment</p></td>
<td><p>Open the oob-topology.xml file in the production environment. Verify that all WSPPackage XML nodes are configured with <strong>generate=true</strong>. If any node is configure with generate=false, then you must change the value to generate=true.</p></td>
</tr>
<tr class="even">
<td><p>Verify identity settings in SharePoint configuration files.</p></td>
<td><div class="alert">

> [!WARNING]
> <P>You must review and configure cookie behavior in SharePoint configuration files. If you do not configure these settings, your Retail online store might display sensitive user information to different users. For example, the default behavior for SharePoint is to use persistent session cookies. This enables a user to close the browser, re-open the browser, and re-visit a SharePoint web application without signing in again. For more information, see <A href="https://go.microsoft.com/fwlink/?linkid=320807">Federated Identity for SharePoint Applications</A>.</P>


</div></td>
</tr>
</tbody>
</table>

  


