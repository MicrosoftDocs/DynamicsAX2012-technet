---
title: Set up an assortment
TOCTitle: Set up an assortment
ms:assetid: 7e0bb912-9ca3-4123-99a8-f887e828128b
ms:mtpsurl: https://technet.microsoft.com/library/Hh597144(v=AX.60)
ms:contentKeyID: 39519200
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- assortment
- assortments
audience: Application User
ms.search.region: Global
---

# Set up an assortment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

To link the products that you sell to the retail channels that sell those products, you must set up *assortments*. Assortments are used to group related products and assign them to a retail channel. You can assign the same product to one or more assortments, and you can assign one or more assortments to the same retail channel.

For example, you create an assortment for a base set of products that all your stores receive. You then create a separate assortment for specialty items that only your larger stores receive.

After you create an assortment and assign it to the appropriate retail channels, you publish the assortment to make the products available in the retail channels.


> [!NOTE]
> <P>Before you can assign an assortment to a retail channel, you must create the store. You must assign this store to an organization hierarchy that is assigned to the <STRONG>Retail assortment</STRONG> purpose. For more information about how to set up an organization hierarchy, see <A href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</A>.</P>



1.  Click **Retail** \> **Common** \> **Assortments**.

2.  On the **Assortments** list page, on the **Action Pane**, in the **New** group, click **Assortment** to create a new assortment. To modify an existing assortment, double-click the assortment in the list.

3.  In the **Assortments** form, on the **General** FastTab, enter a number and name for the assortment.

4.  In the **Effective date** and **Expiration date** fields, define the range of dates that the assortment is valid.
    
    You can enter an effective date that is in the future. In this case, the products that are included in the assortment do not become available to the retail channel until that date. Enter an expiration date to limit the availability of the products that are included in the assortment. If the products that are included in the assortment are always available, leave the default value in the **Expiration date** field.
    

    > [!NOTE]
    > <P>The assortment becomes active at midnight Coordinated Universal Time and expires at 11:59 P.M. Coordinated Universal Time on the dates that you select. The local time zone for the store does not apply to the effective date or expiration date.</P>



5.  Click the **Retail channels** FastTab, and then click **Add line** to add the retail channels that the assortment is assigned to.

6.  In the **Choose organization nodes** form, select the organization hierarchy that contains the retail channels to add. Select the organization nodes or node groups to add, and then click **Add \>\>**. Click **Close** to add the retail channels to the **Retail channels** FastTab.
    

    > [!NOTE]
    > <P>Only organization hierarchies that are assigned to the <STRONG>Retail assortment</STRONG> purpose appear in the <STRONG>Organization hierarchy</STRONG> list.</P>



7.  Click the **Products** FastTab.

8.  To add an individual product category, product, or variant, click **Add line**, and then follow one of these steps:
    
      - In the **Category** field, select a retail product category. Leave the default value in all other fields. All products that are assigned to the selected category are included in the assortment.
    
      - In the **Product** field, select a product. You can filter the list of products by selecting a retail category in the **Category** field.
        

        > [!NOTE]
        > <P>You can add products to an assortment, even if those products have not yet been released to a legal entity. However, the products must be released to a legal entity before the products in the assortment can be available on Microsoft Dynamics AX for Retail POS.</P>

    
      - In the **Product variant** field, select a variant of a product.

9.  To add multiple products and variants at the same time, click **Add products**. Then, in the **Add products** form, do the following:
    
      - Select a retail category hierarchy, and filter the list of products by category.
    
      - In the **Available products** grid, select the check box for each product and product variant to add. Then click **OK** to add the products to the **Products** FastTab.

10. By default, all products that you added to the **Products** FastTab are included in the assortment. To exclude a product from the assortment, on the **Products** FastTab, in the **Line type** field, select **Exclude**.
    
    For example, you can add a category of products, and then exclude specific products in that category. In this case, you add the category as one line item, and then add the category and the products to exclude as a second line item. You then set the line type for the second line item to **Exclude**.

11. On the **Action Pane**, in the **Maintain** group, click **Publish** to start the Retail assortments job and make the assortment available to the retail channels. When the Retail assortments job is completed, the status of the assortment is set to **Published**.

## See also

[Assortments (list page)](https://technet.microsoft.com/library/hh597112\(v=ax.60\))

[Assortment (form)](https://technet.microsoft.com/library/hh580644\(v=ax.60\))

[About setting up assortments](about-setting-up-assortments.md)

[View assortment products](view-assortment-products.md)

[Retail assortments job (form)](https://technet.microsoft.com/library/hh597306\(v=ax.60\))

  


