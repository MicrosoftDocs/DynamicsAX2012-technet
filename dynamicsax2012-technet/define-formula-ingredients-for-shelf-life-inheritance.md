---
title: Define formula ingredients for shelf life inheritance
TOCTitle: Define formula ingredients for shelf life inheritance
ms:assetid: 4415aa93-c08e-449a-b7c7-bbe56b253875
ms:mtpsurl: https://technet.microsoft.com/library/JJ838733(v=AX.60)
ms:contentKeyID: 50120616
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define formula ingredients for shelf life inheritance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can select ingredients that are used to update the shelf life information for finished items. If you select an ingredient that is a shelf life item, the **Inherit shelf life dates to end item** check box is available in the **Formula line** form. If the formula version contains co-products that are configured as shelf life items, the **Inherit shelf life dates to co-product** check box is available in the **Formula line** form.

You can select all the shelf life ingredients based on which the earliest shelf life dates (the best-before date and the expiration date) are calculated and updated for the finished items.

After you define the formula ingredients based on the shelf life ingredients, you can create batch orders and process the finished items and any related co-products. After you run the report as finished process, the calculated earliest shelf life dates (the best-before date and the expiration date) are updated in the inventory batches for the finished item and any related co-products.

Use this procedure to define formula ingredients for shelf life inheritance.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a released product, and then click **Edit**. or on the **Action Pane**, click **Product** to create a released product. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  In the **Released product details** form, on the **Action Pane**, on the **Product** tab, click **Dimension group**.

4.  In the **Storage dimension group** and **Tracking dimension group** fields, select a storage dimension group and tracking dimension group for the item. Click **OK**.

5.  Click the **Engineer** FastTab, and then in the **Production type** field, select **Formula**.

6.  On the **Action Pane**, click the **Engineer** tab, and then in the **Formula** group, click **Lines**.
    

    > [!NOTE]
    > <P>The <STRONG>Lines</STRONG> button is available only if <STRONG>Formula</STRONG> or <STRONG>Planning item</STRONG> is selected in the <STRONG>Production type</STRONG> field on the <STRONG>Engineer</STRONG> FastTab for the released product.</P>



7.  In the **Formula line** form, click **New** to create a formula.

8.  In the **Formula** field, select the identification code of a formula. For more information, see [Create a formula and formula version](create-a-formula-and-formula-version.md).

9.  In the lower pane, click **New** to add an ingredient.

10. In the **Item number** field, select the identification code of a shelf life item. For more information, see [Set up an item as a shelf life item](set-up-an-item-as-a-shelf-life-item.md).

11. Click the **Setup** tab.

12. Select the **Inherit shelf life dates to end item** check box to indicate that the shelf life dates of the ingredient are inherited by the finished item.
    

    > [!NOTE]
    > <P>This check box is available only if you select a shelf life item in the <STRONG>Item number</STRONG> field.</P>



13. Select the **Inherit shelf life dates to co-product** check box to indicate that the shelf life dates of the co-product are inherited by the finished item.
    

    > [!NOTE]
    > <P>This check box is available only if you select a formula version that contains co-products that are configured as shelf life items in the <STRONG>Formula</STRONG> field.</P>



## See also

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

[(PM) Released product details (form)](https://technet.microsoft.com/library/hh352306\(v=ax.60\))

  


