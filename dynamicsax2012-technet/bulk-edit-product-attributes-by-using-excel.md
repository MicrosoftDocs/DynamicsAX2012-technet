---
title: Bulk edit product attributes by using Excel
TOCTitle: Bulk edit product attributes by using Excel
ms:assetid: 2f912571-eb34-4d82-a207-36681e67b35c
ms:mtpsurl: https://technet.microsoft.com/library/Dn268413(v=AX.60)
ms:contentKeyID: 54916951
author: Khairunj
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- Excel
- attributes
- export
- product attributes
audience: Application User
ms.search.region: Global
---

# Bulk edit product attributes by using Excel 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to use Microsoft Excel to update attributes such as size, color, and dimensions for products that you sell in your retail channels. You can use Excel to update attributes for products in a catalog, and, if you’re using AX 2012 R3, to update products that aren’t included in a catalog.

In Microsoft Dynamics AX 2012 for Retail, you use product attributes to add merchandising details to the products that you offer in your online store. Product attributes include things like color, size, product dimensions, and other product details. To make product attributes visible in the online store, you add them to the products that are listed in your retail catalog.

You can edit product attributes at any time. You can edit them one by one in the retail catalog by using the **Catalog details** form, or you can bulk edit them by exporting them to Excel, editing them there, and then importing the changes back into the retail catalog. In Excel, you can edit product attributes for the entire catalog or you can edit only the product attributes that are assigned to a specific category.

**Using Excel in AX 2012 R3**

You can use Excel to bulk edit product attributes for products offered in any retail channel, whether or not they are included in a retail catalog. In AX 2012 R3, bulk editing product attributes in Excel is even easier. Enhancements to functionality allow you to do the following:

  - Easily identify required attributes.

  - Enter URLs for images and videos directly in the spreadsheet and upload that data back to Microsoft Dynamics AX.

  - Select the appropriate value from a fixed list when multiple values are assigned to a specific attribute.

  - More easily assign an appropriate value to attributes that include a minimum and maximum value range. If minimum and maximum value ranges aren’t defined for an attribute, the minimum and maximum value ranges that are defined for the system are used.

## Prerequisites

Before you can use Excel to bulk edit product attributes in a retail catalog, complete the following tasks.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enable digitally signed macros and disable all other macros in Excel.</p></td>
<td><p><a href="configure-clients-computers-to-bulk-edit-attributes-in-microsoft-excel.md">Configure clients computers to bulk edit attributes in Microsoft Excel</a></p></td>
</tr>
<tr class="even">
<td><p>Define product attributes.</p></td>
<td><p><a href="set-up-attributes-and-attribute-types.md">Set up attributes and attribute types</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up attribute groups.</p></td>
<td><p><a href="set-up-retail-attribute-groups.md">Set up retail attribute groups</a></p></td>
</tr>
<tr class="even">
<td><p>Assign attribute groups to retail categories or retail channels.</p></td>
<td><p><a href="set-up-a-retail-hierarchy.md">Set up a retail hierarchy</a></p>
<p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a retail catalog.</p>
<div class="alert">

> [!NOTE]
> <P>If AX 2012 R3 is installed, you can update product attributes in a retail catalog that is assigned to a retail store, online store, or call center. You can also update product attributes outside of a retail catalog by using the <STRONG>Channel product attributes</STRONG> form.</P>


</div></td>
<td><p><a href="key-tasks-create-retail-product-catalogs.md">Key tasks: Create retail product catalogs</a></p>
<p><a href="add-and-update-product-attributes-for-retail-channels.md">Add and update product attributes for retail channels</a></p></td>
</tr>
<tr class="even">
<td><p>Install Microsoft Office Add-ins for Microsoft Dynamics AX.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=301289">Install Office Add-ins</a></p></td>
</tr>
</tbody>
</table>


## Bulk edit attributes for products that are included in a retail catalog

This procedure applies to all versions of Retail in AX 2012. If you are using AX 2012 R3, you must complete some additional steps as described later in this section.

Follow this procedure to use Excel to bulk edit attributes for products in a retail catalog.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.
    

    > [!NOTE]
    > <P>If the catalog has already been published, clicking <STRONG>Edit</STRONG> changes the catalog status to a status of <STRONG>Draft</STRONG>.</P>



3.  In the **Catalogs** form, do one of the following:
    
      - To edit all product attributes in the catalog: In the category navigation pane, select the root node, and then click **Edit in Excel**.
    
      - To edit only attributes that are assigned to products in a specific category: In the category navigation pane, select the category, and then click **Edit in Excel**.
    
    It may take a few moments for Excel to open and the attributes to appear.

4.  In Excel, edit the attributes for the products in the categories that you selected.

5.  When you are finished editing the attributes, in Excel, click the **Dynamics AX** tab, and then in the **Update** group, click **Publish**.
    
    This process may take a few moments.

6.  After the publishing process is completed, you can close Excel.

To verify your changes, in the **Catalogs** form, do the following:

1.  In the category navigation pane, select a category.

2.  On the **Products** FastTab, select a product in the grid, and then click **Attributes**.

**Additional steps for AX 2012 R3**

If AX 2012 R3 is installed, you must publish the updated data and then send it to the stores.

To publish the updated product attributes, follow these steps:

1.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Publish**.

2.  In the **Publish catalog** form, in the **Publish** field, select one of the following options:
    
      - **Only products that have changed** – Select this option to publish only the changes that were made to a catalog since it was last published.
    
      - **All products** – Select this option if this is the first time the catalog is being published, or if you want to republish the whole catalog.

After the catalog publishing process is complete, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, in the left pane, in the **Name** column, select the **1150** (Catalog) scheduler job.

3.  To run the job manually or in batch mode, do one of the following:
    
      - To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**.
    
      - To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that is displayed, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## In AX 2012 R3: Bulk edit attributes for products outside of a retail catalog

To update the attributes for products in a catalog, follow the preceding procedure. In AX 2012 R3, you can also bulk edit attributes for products that are offered in any retail channel. If the products are offered outside of a catalog you can add or modify attributes for any product and publish the data to your stores without the overhead of creating and maintaining a product catalog. If the products are also offered in a catalog, you can add or maintain the product attributes at the retail channel level and then use the catalog publishing process that is described in the preceding procedure to upload the new product attributes to your catalogs and stores.

To use Excel to bulk edit retail product attributes outside of a catalog, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**. In the **Retail stores** list, open a retail store.
    
    –or–
    
    Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, open an online store.
    
    –or–
    
    Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**. In the **Call centers** list, open a call center.

2.  In the form that opens, on the **Action Pane**, on the **Set up** tab, click **Store product attributes**.

3.  In the **Channel product attributes** form, click **Edit**. Then do one of the following:
    
      - To edit all product attributes in the organization: In the navigation pane, select the root node, and then click **Edit in Excel**.
    
      - To edit attributes that are assigned to products in a specific category of stores: In the navigation pane, select the category, and then click **Edit in Excel**.
    
      - To edit attributes that are assigned to products in a specific store: In the navigation pane, select the store, and then click **Edit in Excel**.
    
    It may take a few moments for Excel to open and the attributes to appear in the worksheet.

4.  In Excel, edit the attributes for the products in the areas that you selected.

5.  When you are finished editing the attributes, in Excel, click the **Dynamics AX** tab, and then in the **Update** group, click **Publish**.
    
    This process may take a few moments.

6.  After the publishing process is completed, you can close Excel.

7.  To verify your changes, in the **Channel product attributes** form, do one of the following:
    
      - In the left navigation pane, select the root node, a category of stores, or a store.
    
      - On the **Attribute group** FastTab, select an attribute group in the list, and click **View attributes**.
    
      - On the **Products** FastTab, select a product in the list, and click **Attributes**.

8.  After you have verified your attribute changes, click **Publish channel updates**.

To send the updated attribute data to the stores, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, in the left pane, in the **Name** column, select the **1070** (Channel configuration) scheduler job.

3.  To run the job manually or in batch mode, do one of the following:
    
      - To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**.
    
      - To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that is displayed, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## See also

[Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md)

[Add and update product attributes for retail channels](add-and-update-product-attributes-for-retail-channels.md)

[Set up retail attribute groups](set-up-retail-attribute-groups.md)

[Set up attributes and attribute types](set-up-attributes-and-attribute-types.md)

  


