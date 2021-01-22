---
title: Configure print settings for labels
TOCTitle: Configure print settings for labels
ms:assetid: d2e530b9-638a-40d8-9b82-8cb5d105238b
ms:mtpsurl: https://technet.microsoft.com/library/Dn553203(v=AX.60)
ms:contentKeyID: 62200162
author: Khairunj
ms.author: daxcpft
ms.date: 05/28/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure print settings for labels 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to enable workers to print or reprint labels. You can configure Microsoft Dynamics AX to print labels either automatically or manually for each warehouse process. For example, you can set up the system to print labels during receiving or production put-away.

## Overview of print settings for labels

To enable workers to print or reprint labels, you must configure settings in the following forms.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Printer</strong></p></td>
<td><p>Ensure that the printer is configured to accept RAW commands. Typically, this is specified in the Control Panel application in the properties for the printer. For more information about printer settings for RAW commands, see the documentation for your device.</p></td>
</tr>
<tr class="even">
<td><p><strong>Warehouse management parameters</strong></p></td>
<td><p>Specify your company’s GS1 prefix if you want to include it on labels.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Document routing layouts</strong></p></td>
<td><p>Define the information that is included in the label and the sequence that it is arranged in. This is the command that is sent to the printer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Document routing</strong></p></td>
<td><p>Define the print settings for specific types of work orders, such as transfer order receipts and return orders.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Work templates</strong></p></td>
<td><p>Create a print step that specifies when to print labels for specific types of work orders, such as sales orders. For more information, see <a href="create-a-work-template.md">Create a work template</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Mobile device menu items</strong></p></td>
<td><p>Configure the mobile device menu items that workers can use to print or reprint labels from mobile devices.</p></td>
</tr>
</tbody>
</table>


## Optional: Include your GS1 prefix on labels

If you are a GS1 member company you can include your GS1 company prefix on labels. When you set up the layout for labels, as described later in this topic, you can add the GS1 company prefix to the layout.

To specify your GS1 company prefix, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  On the **GS1 company prefix** tab, on the **Company information** FastTab, in the **GS1 company prefix** field, enter the GS1 prefix.


> [!NOTE]
> <P>The settings on the <STRONG>Print management</STRONG> tab are not used for printing labels.</P>



## Set up the layout and the information to include on a label

You must set up one or more document routing layouts that specify the information that is included and the order in which this information is organized on a label. For each document routing layout, you specify a print command that defines the information and arrangement. Depending on the label printer that you use, you can define the print command to display labels as plain text, bar code, or both.

Predefined placeholders are available for document routing layouts. You can use these placeholders to include information from Microsoft Dynamics AX as plain text in the label.

For bar codes, the print command must be in the page description language (PDL) that is used by the label printer. Examples of PDLs are the Zebra Programming Language (ZPL and ZPL II) and Sato Barcode Programming Language (SBPL). For information about the PDL that your label printer uses, see the documentation for that device. Typically, the print command for a bar code is created in a label design program and then copied to the **Label layout** field in the **Document routing layouts** form. After you have copied the print command, you can add one or more placeholders. The following example is a print command for a document layout in ZPL, and includes the $ItemID$ placeholder that inserts an item ID.

${^XA^FO10,10,^AO,30,20^$ItemID$^FS^FO10,30^BY3^BCN,100,Y,N,N^$ItemID$^FS^XZ}$

To set up a document routing layout, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Document routing** \> **Document routing layouts**.

2.  Click **New** to create a new layout.

3.  In the **Layout ID** and **Description** fields, enter a unique identifier and a name for the layout.

4.  On the **Label layout** FastTab, define the label layout by entering a command that uses the PDL that is required by your label printer. To add placeholders, right-click the field, and then select the placeholder to add to the label.

## Define print settings for work orders, and specify the printer to use

You can create document routings to specify print settings for different types of work orders. You can also create one or more document routings for each type of work order. The settings for each document routing apply to a selected warehouse. You can set up a query for each document routing, so that the routing is applied when certain conditions are met.


> [!NOTE]
> <P>A predefined query is available for printing license plate labels. You can add more conditions to the query. To reset the query to the default settings, click the <STRONG>Reset query</STRONG> button on the <STRONG>Document routing</STRONG> form. When you reset the query, any conditions that were added will be deleted.</P>



To set up document routes for work orders, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Document routing** \> **Document routing**.

2.  In the **Work order type** field, select the type of work order to create the document routing for. Click **New**.

3.  In the **Sequence number** field, enter a number to define the position of the document routing in the routing hierarchy.

4.  In the **Name** field, enter a name for the document routing. This should indicate the purpose of the document routing.

5.  Optional: On the **Overview** FastTab, fill in the fields as described in the following table. These fields are used as criteria to determine when to use the document routing. The criteria can be applied alone or together with the query that you define for this document routing.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Enter the name of the computer that will be used to connect to the label printer.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mobile device user ID</strong></p></td>
    <td><p>Select the ID of the mobile device user who this document routing is for. For more information, see <a href="set-up-mobile-device-user-accounts-for-workers.md">Set up mobile device user accounts for workers</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Account number</strong></p></td>
    <td><p>Select the vendor account that this document routing is for.</p>
    <p>This option is available only for the following work order types: purchase orders, sales orders, and return orders.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Carrier</strong></p></td>
    <td><p>Select the carrier that this document routing is for.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Work template code</strong></p></td>
    <td><p>Select the work template that this document routing is for.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>From zone ID</strong> and <strong>To zone ID</strong></p></td>
    <td><p>To apply this document routing to a range of zones, select the zones to define the start and end points for the range.</p></td>
    </tr>
    </tbody>
    </table>


6.  To enable the query, select the **Run query** check box. If you do not select this check box, the optional fields described in step 5 are used to determine who can print labels for the selected type of work order.

7.  On the **Document routing printers** FastTab, in the **Printer name** field, enter the full name of the printer to use.

8.  In the **Layout ID** field, select the document routing layout that contains the information and structure to use for the label.

## Add a print step to the work template for each type of work order

You can specify when to print labels by adding a print step to a work template. The print step will require the worker to print the label at the point in the process where you place it. For example, if you want a worker to print a label after the item is put away, you can place the print step after the put step in the sequence of steps.


> [!NOTE]
> <P>If you specify a print step in the work template, we recommend that you do not select the <STRONG>Print label</STRONG> check box on the mobile device menu item. If you enable label printing for the mobile device, labels are always printed as the last step in the work template, regardless of the position of the print step.</P>



To add a print step to a work template, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work templates**.

2.  Create or select a work template. For more information, see [Create a work template](create-a-work-template.md).

3.  On the lower pane, click **New** to add a new line for the work template.

4.  In the **Work type** field, select **Print**.

5.  In the **Work class ID** field, select the work class that controls access to the work for the selected work order type. Typically, this is the same work class that is used by the pick and put work types. Unlike work types for picking and put away, where you must add one put away for every pick, you can add a single work type for printing.

## Enable workers to print or reprint labels by using a mobile device

You can set up mobile device menu items that enable a worker to use their mobile device to print or reprint labels. For more information, see Configure the work that can be done using mobile devices.

**Enable workers to use mobile devices to print labels**

To enable workers to use mobile devices to print labels, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Create a new menu item for a mobile device.

3.  In the **Menu item name** and **Title** fields, enter a name for the menu item and the title to display on the mobile device.

4.  In the **Work creation process** field, select the appropriate work type.

5.  In the **Work template code** field, select the work template that you want to use for the work type that you selected. When you select a work template, labels are printed according to the position of the printing step that is defined on the work template. For more information, see the “Add a print step to the work template for each type of work order” section earlier in this topic.

6.  Select the **Print label** check box to print a label only after all steps in the work template have been completed.
    

    > [!NOTE]
    > <P>If the <STRONG>Print label</STRONG> check box is selected, labels are always printed for the work order. This is true regardless of whether a print step is included in the work template. Additionally, if a work template does include a print step, the position of the step in the sequence is disregarded and labels are always printed last. This is useful if you always want to print labels at the end of the process.</P>
    > <P>If you want to use the work template to print labels at a specific point in the process, do not select this check box.</P>



**Enable workers to use mobile devices to reprint labels**

To configure mobile device menu items to reprint labels, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Create a new menu item for a mobile device.

3.  In the **Menu item name** and **Title** fields, enter a name for the menu item and the title to display on the mobile device.

4.  In the **Activity code** field, select **Reprint label** to reprint a previously printed label.

## Next step

The next step in this process is to add the menu items to a mobile device menu in order to make them available to workers. For more information, see [Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md).

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


