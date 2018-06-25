---
title: 'Walkthrough: Integrating New Reports into Microsoft Dynamics AX'
TOCTitle: 'Walkthrough: Integrating New Reports into Microsoft Dynamics AX'
ms:assetid: 7f194346-07a9-4aee-b602-2a4e4f5c5af6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc600454(v=AX.60)
ms:contentKeyID: 28119389
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Integrating New Reports into Microsoft Dynamics AX [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a report, and then integrate the report into Microsoft Dynamics AX. After the report is in Microsoft Dynamics AX, you will create an output menu item for the report and display the report on a menu within the application.

This walkthrough illustrates the following tasks:

  - Creating a report

  - Displaying a report on a menu in Microsoft Dynamics AX

  - Deploying a report project to a report server

  - Verifying the results

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the InventTable table. In order to view data in the report, this table must be populated with data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

  - Your own label file


> [!NOTE]
> <P>If you do not have a label file, use the label file wizard in Microsoft Dynamics AX to create a label file. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa844896(v=ax.60)">How to: Create a Label File</A>.</P>



## Creating a Report

You will start by creating a reporting project that contains a report that will be integrated into Microsoft Dynamics AX.

### To create the report

  - Complete the steps in [Walkthrough: Creating an Auto Design Report](walkthrough-creating-an-auto-design-report.md).

  - In the AOT, expand **Visual Studio Projects** \> **Dynamics AX Model Projects**. Notice that the report project called **SampleItemReport** has been added in the layer that you are currently working in.
    

    > [!NOTE]
    > <P>If you do not see the report project, restart the Microsoft Dynamics AX client to update the metadata cache.</P>



## Displaying a Report on a Menu in Microsoft Dynamics AX

Now that the project is available in Microsoft Dynamics AX, you are ready to use the report in the application. An output menu item is used for an application object whose primary function is to display a result, such as a report. The following procedures explain how to create an output menu item for the report, and then add the output menu item to a menu in the Inventory and warehouse management module.

### To create a menu item for the report

1.  In the AOT, expand the **Menu Items** node.

2.  Right-click the **Output** node, and then click **New Menu Item**.

3.  Select the node for the menu item.

4.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>ItemList</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Label</strong></p></td>
    <td><p>Click the ellipsis button (…) to display the label editor. In the label editor, click the <strong>Setup</strong> tab, and then select your label file from the <strong>Label file ID</strong> field. Click the <strong>Label</strong> tab. Press CTRL+N to create a new label. Type <strong>Item list</strong> for the label text. Press CTRL+S to save the label. Mark the check box for the new label and click <strong>Paste label</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ObjectType</strong></p></td>
    <td><p><strong>SSRS Report</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Object</strong></p></td>
    <td><p><strong>ItemReport</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Report Design</strong></p></td>
    <td><p>AutoDesign1</p></td>
    </tr>
    </tbody>
    </table>


5.  In the AOT, click **Save All** to save the changes.

### To display the report on a menu in the Inventory and warehouse management module

1.  In the AOT, expand the **Menus** node.

2.  Expand the **InventoryAndWarehouseManagement** node, expand the **Reports** node, right-click the **Base data** node, point to **New**, and then click **Menu item**.

3.  Select the node for the menu item.

4.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>MenuItemType</strong></p></td>
    <td><p><strong>Output</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>MenuItemName</strong></p></td>
    <td><p><strong>ItemList</strong></p></td>
    </tr>
    </tbody>
    </table>


5.  Drag-and-drop the **ItemList** menu item so that it is the first item listed in the **Base data** folder.

6.  In the AOT, click **Save All** to save the changes.

## Deploying a Report Project to a Report Server

In order to view the report in the application, the report must be deployed to a report server. You can deploy reports to a report server from within Microsoft Dynamics AX. The following procedure explains how to deploy the report project to a report server from within Microsoft Dynamics AX.

### To deploy a report project to the report server

1.  In the AOT, expand the **SSRS Reports** node. A report named **ItemReport** displays below the **SSRS Reports** node.

2.  Right-click the **ItemReport** node, and then click **Deploy Element**.

## Verifying the Results

Next, you will verify that the report displays along with the other reports in the Inventory and warehouse management module.

### To verify the results

1.  Open the Navigation Pane if it is not already open. Click **Microsoft Dynamics AX** \> **View** \> **Navigation Pane**.

2.  Select the **Inventory and warehouse management** module.

3.  In the Navigation Pane, expand the **Reports** node, expand the **Base data** node, and then click the **Item list** node. The report displays.
    

    > [!NOTE]
    > <P>If you do not see the report display as a menu item in the Inventory and warehouse management module, restart the Microsoft Dynamics AX client to update the metadata cache.</P>



## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md)

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

