---
title: 'How to: Customize a Report'
TOCTitle: 'How to: Customize a Report'
ms:assetid: 334e03ba-cee1-4a45-83a7-9b0030802367
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc569485(v=AX.60)
ms:contentKeyID: 28119336
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Customize a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to customize an existing report for Microsoft Dynamics AX. It describes how to change the development layer you are working in, how to access a report for edit, and how to deploy the report to the report server.

## Changing the Development Layer

Reports in Microsoft Dynamics AX adhere to the layered development structure in the MorphX development environment. When you customize an existing report, a copy of the reporting project for the layer that you are currently working in is created and opened in Microsoft Visual Studio where it can be edited and later saved to the AOT. Before you customize a report, make sure that you are working in the correct development layer.

### To change the development layer

1.  Open the Microsoft Dynamics AX Server Configuration utility (**Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**).

2.  Create a new configuration to point at the development layer.
    
    Click **Manage** and then click **Create configuration**. In the Create Configuration window, name the new configuration, such as "VARLayer".
    

    > [!NOTE]
    > <P>It is a good practice to name the configuration with the name of the layer such as USR or VAR layer.</P>



3.  On the **Developer** tab, select the correct layer from the drop-down list in the **Application object layer to open** field, and then click **OK**.
    

    > [!NOTE]
    > <P>The configuration utility runs outside of Microsoft Dynamics AX. You must stop and restart the client for the changes to take effect.</P>



4.  Click **OK** to close the configuration window.

## Editing the Report

You will edit Microsoft Dynamics AX reports in Visual Studio. You can access a report for edit from the AOT or from Visual Studio. It is faster to access a report for edit from the Application Explorer. The following sections describe how to access a report for edit from the AOT and from Visual Studio.

### To access a report for edit from the AOT

1.  Start Microsoft Dynamics AX \> **New Development Workspace**. If User Account Control (UAC) is active, be sure you start Microsoft Dynamics AX with administrative privileges.

2.  In the AOT, expand the **Visual Studio Projects** node, and then expand the **Dynamics AX Model Projects** node.

3.  Right-click the report project that you want to edit and click **Edit**. For a list of the projects and reports they contain, see [List of Reporting Projects](list-of-reporting-projects.md).
    
    The selected project opens in Microsoft Visual Studio where you can edit or customize the reports.

4.  To save the changes to the report, from the **File** menu, click **Save “report name”** or click **Save All** to save the project.

### To access a report for edit from Visual Studio

1.  Start Visual Studio. If User Account Control (UAC) is active, be sure you start Visual Studio with administrative privileges.
    

    > [!NOTE]
    > <P>If a report is edited without administrative privileges, then it cannot be deployed.</P>



2.  In Application Explorer, expand the **Visual Studio Projects** node, and then expand the **Dynamics AX Model Projects** node.

3.  Right-click the report project that you want to edit and click **Edit**. For a list of the projects and reports they contain, see [List of Reporting Projects](list-of-reporting-projects.md).
    
    The selected project opens in Microsoft Visual Studio where you can edit or customize the reports.

4.  To save the changes to the report, from the **File** menu, click **Save “report name”** or click **Save All** to save the project.

## Deploying the Report

You must deploy the customized report to see the changes in Microsoft Dynamics AX. There are two ways to do this.

  - Build and deploy from within Visual Studio.

  - Build in Visual Studio, and then deploy from the AOT.

The following procedures describe how to deploy the report from Visual Studio and the AOT.

### To build and deploy from Visual Studio

  - In Solution Explorer, right-click the project and then click **Build** or **Deploy**. When you build a reporting project, customizations are saved directly into the AOT. When you deploy a reporting project from Visual Studio, a build operation is performed that saves the changes to the AOT, and then the updated report is deployed to the report server.

### To build from Visual Studio and deploy in the AOT

  - In Solution Explorer, right-click the project and then click **Build**. When you build a reporting project, customizations are saved directly into the AOT.

  - Open Microsoft Dynamics AX.

  - In the AOT, expand the **SSRS Reports** node and expand the **Reports** node.

  - Right-click the report that contains the customizations and then click **Deploy Element**. The updated report is deployed to the report server.

## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[Walkthrough: Customizing Existing Microsoft Dynamics AX Reports](walkthrough-customizing-existing-microsoft-dynamics-ax-reports.md)

