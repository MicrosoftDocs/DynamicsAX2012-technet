---
title: Add and update product attributes for retail channels (Retail essentials)
TOCTitle: Add and update product attributes for retail channels (Retail essentials)
ms:assetid: 7fed2812-d8ff-40e0-8a1c-eb19b277cf31
ms:mtpsurl: https://technet.microsoft.com/library/Dn876696(v=AX.60)
ms:contentKeyID: 63384782
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Add and update product attributes for retail channels (Retail essentials) 


This topic describes how to set up product attributes that can be applied to products that are offered in your stores. You can use product attributes to add merchandising details, such as rich text, images, and videos to the descriptions of products that you offer in your retail stores or in product catalogs. By adding merchandising details to products, you can provide the product information that your staff needs to better serve the customer. Product attributes can be applied to products even if they are not included in a retail product catalog.

You can add or modify product attributes for individual products, categories of products, or for all stores that are assigned to a selected category. You can also bulk edit product attributes by using Microsoft Excel. For more information about how to bulk edit product attributes by using Excel, see Bulk edit product attributes in a Retail catalog using Microsoft Excel (Retail essentials).

After you update the product attributes, you must publish your changes to upload the new data to your stores.

## Prerequisites

Before you can maintain channel product attributes, you must first complete the following task:

  - Set up attribute groups. For more information, see [Set up retail attribute groups (Retail essentials)](set-up-retail-attribute-groups-retail-essentials.md).

## Set up product attributes

1.  Click **Retail essentials** \> **Channels** \> **Retail stores**. In the **Retail stores** list, open a retail store.

2.  In the **Stores** form, on the **Action Pane**, on the **Set up** tab, click **Store product attributes**.

3.  In the **Channel product attributes** form, click **Edit**.

4.  In the left pane, select the store that you want to add product attributes to.

5.  On the **General** FastTab, do the following:
    
      - Select the **Inherit** check box if you want the selected store to inherit attributes, attribute values, attribute metadata, and category hierarchy assignments from the parent store.
        

        > [!WARNING]
        > <P>If you select this check box after you have assigned attribute groups or attribute metadata to the store, those values will be overridden and replaced with the attribute data from the parent store. You can manually re-enter any values that were overridden that still apply to the store.</P>

    
      - Select the category hierarchy that applies to the store. This hierarchy is used to browse through products by category in the channel.

6.  On the **Attribute group** FastTab, click **Add** to add the attribute groups that apply to the selected store. By assigning attribute groups to a selected store, you can quickly assign multiple attribute values to all products in the store at the same time. To view the attributes that are included in an attribute group, click **View attributes**.

7.  On the **Products** FastTab, view the list of products that have been assorted to the selected store. You can also do the following:
    
      - Click **Add** to open the **Add products** form and add products to the selected store.
    
      - Click **Attributes** to view the attribute values that are assigned to a selected product.
    
      - Click **Retail channels** to view the retail channels that a product is assorted to.

8.  To map attribute metadata for product attributes that are added to the store, click the **Setup** tab, and then click **Set attribute metadata**.

9.  In the **Set attribute metadata** form, in the **Category hierarchy** field, select the category hierarchy that you want to set attribute metadata for, and then, in the left pane, select a category.

10. Select the options that indicate how the attributes for each category or channel product should behave. For example, you can select whether attributes are required, whether they can be used for search, and whether they can be used as a filter. To view the various metadata options for the product attributes, select the **Include attribute** check box.

11. To add attributes and attribute metadata to other stores in the organization hierarchy, repeat steps 4 through 10.
    
    To maintain product attributes in bulk, in the **Channel product attributes** form, on the **Internal organization** tab, click **Edit in Excel**. For more information about how to bulk edit product attributes by using Excel, see Bulk edit product attributes in a Retail catalog using Microsoft Excel (Retail essentials).

12. Click **Publish channel updates**, and then complete the following procedure to send the attribute data to the stores.

## Send updated product attributes to stores

Use this procedure to send the updated product attributes to stores. You must run the following scheduler jobs:

  - **1070** (Channel configuration).

  - **1150** (Catalog), if Microsoft Dynamics AX 2012 R3 is installed and a retail product catalog is assigned to the retail store.

To run scheduler jobs, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Distribution schedule**.

2.  In the left pane, in the **Name** column, select the job that you want to run. To run the job manually or in batch mode, do one of the following:
    
      - To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**.
    
      - To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that is displayed, enter information about the batch job.

## See also

[Set up retail attribute groups (Retail essentials)](set-up-retail-attribute-groups-retail-essentials.md)

  


