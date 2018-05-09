---
title: Set up an assortment (Retail essentials)
TOCTitle: Set up an assortment (Retail essentials)
ms:assetid: 5a059bf3-f3d9-4d3c-b5c7-94af0cca4193
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736884(v=AX.60)
ms:contentKeyID: 62200362
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up an assortment (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up assortments, so that you can link the products that you sell to the retail channels that sell those products. Assortments are used to group related products and assign them to a retail channel. You can assign the same product to one or more assortments, and you can assign one or more assortments to the same retail channel.

For example, you create an assortment for a base set of products that all your stores receive. You then create a separate assortment for specialty items that only your larger stores receive.

After you create an assortment and assign it to the appropriate retail channels, you publish the assortment to make the products available in the retail channels.

Before you can assign an assortment to a retail channel, you must create the store. You must assign this store to an organization hierarchy that is assigned to the **Retail assortment** purpose. For more information about how to set up an organization hierarchy, see [Working with organizations and organizational hierarchies (Retail essentials)](working-with-organizations-and-organizational-hierarchies-retail-essentials.md).


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Merchandising** \> **Assortments**.

2.  On the **Assortments** list page, on the **Action Pane**, in the **New** group, click **Assortment** to create a new assortment. To modify an existing assortment, double-click the assortment in the list.

3.  In the **Assortments** form, on the **General** FastTab, enter an ID and name for the assortment.

4.  In the **Effective date** and **Expiration date** fields, define the range of dates that the assortment is valid.
    
    You can enter an effective date that is in the future. In this case, the products that are included in the assortment do not become available to the retail channel until that date.
    
    Enter an expiration date to limit the availability of the products that are included in the assortment. If the products that are included in the assortment are always available, leave the default value in the **Expiration date** field.
    

    > [!NOTE]
    > <P>The assortment becomes active at midnight Coordinated Universal Time (UTC) on the effective date that you select and expires at 11:59 P.M. UTC on the expiration date that you select. The local time zone for the store does not apply to the effective date or expiration date.</P>



5.  On the **Retail channels** FastTab, click **Add line** to add the retail channels that the assortment is assigned to.

6.  In the **Choose organization nodes** form, select the organization hierarchy that contains the retail channels to add. Select the organization nodes or node groups to add, and then click **Add \>\>**. Click **Close** to add the retail channels to the **Retail channels** FastTab.
    

    > [!NOTE]
    > <P>Only organization hierarchies that are assigned to the <STRONG>Retail assortment</STRONG> purpose appear in the <STRONG>Organization hierarchy</STRONG> list.</P>



7.  Click the **Products** FastTab.

8.  To add an individual product category, product, or variant, click **Add line**, and then follow one of these steps:
    
      - In the **Category** field, select a retail product category. Leave the default value in all other fields. All products that are assigned to the selected category are included in the assortment.
    
      - In the **Product** field, select a product. You can filter the list of products by selecting a retail category in the **Category** field.
        

        > [!NOTE]
        > <P>You can add products to an assortment, even if those products have not yet been released to a legal entity. However, the products must be released to a legal entity before the products in the assortment can be available in Retail essentials.</P>

    
      - In the **Product variant** field, select a variant of a product.

9.  To add multiple products and variants at the same time, click **Add products**. Then, in the **Add products** form, follow these steps:
    
    1.  Select a retail category hierarchy, and filter the list of products by category.
    
    2.  In the **Available products** grid, select the check box for each product and product variant to add. Then click **Add** to add the products to the list of selected products.
    
    3.  Click **OK** to add the selected products to the **Products** FastTab in the **Assortments** form.

10. By default, all products that you added to the **Products** FastTab are included in the assortment. To exclude a product from the assortment, on the **Products** FastTab, in the **Line type** field, select **Exclude**.
    
    For example, you can add a category of products and then exclude specific products in that category. In this case, you add the category as one line item, and then add the category and the products that should be excluded as a second line item. You then set the line type for the second line item to **Exclude**.

11. On the **Action Pane**, in the **Maintain** group, click **Publish** to start the Retail assortments job and make the assortment available to the retail channels. When the Retail assortments job is completed, the status of the assortment is set to **Published**.

## See also

[Assortments (Retail essentials)](assortments-retail-essentials.md)

[View assortment products (Retail essentials)](view-assortment-products-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

