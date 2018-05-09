---
title: Define and activate formula ingredients for batch attribute inheritance
TOCTitle: Define and activate formula ingredients for batch attribute inheritance
ms:assetid: a92bb607-fccb-403a-9d40-625467f77d05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838745(v=AX.60)
ms:contentKeyID: 50120628
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Define and activate formula ingredients for batch attribute inheritance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can select ingredients that are used to update the product characteristic or batch attribute information for finished items. If you select an ingredient for which you have specified the same batch attributes in the **Product specific** form as for the finished item, the **Inherit batch attributes to end item** check box is available in the **Formula line** form. If the formula version contains co-products, the **Inherit batch attributes to co-product** check box is available in the **Formula line** form.

You can select all the batch attribute ingredients for which the batch attributes are updated for the finished items. If multiple ingredients are associated with the same batch attribute, you can select only one ingredient to update for the finished items.

You can select batch attributes from each ingredient to update batch attribute information for the finished items. If multiple ingredients have different batch attributes, you can select the batch attributes to apply and activate the batch attribute transfer. However, if there is an ingredient that has the same batch attributes as another ingredient, you cannot activate the batch attribute transfer.

You can approve and activate the formula version after you select all the active batch attributes.

After you define and activate batch attributes in the formula ingredients, you can create batch orders and process the finished item and any related co-products. After you run the report as finished process, the active batch attributes are updated in the inventory batches for the finished item and related co-products.

## Configure formula ingredients for batch attribute inheritance

Use this procedure to select the ingredients that are used to update the product characteristic or batch attribute information for finished items.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a released product, and then click **Edit**, or on the **Action Pane**, click **Product** to create a released product. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  In the **Released product details** form, on the **Action Pane**, on the **Product** tab, click **Dimension group**.

4.  In the **Storage dimension group** and **Tracking dimension group** fields, select a storage dimension group and tracking dimension group for the item, and then click **OK**.

5.  Click the **Engineer** FastTab, and then in the **Production type** field, select either **Formula** or **Planning item**.

6.  On the **Action Pane**, click the **Engineer** tab, and then in the **Formula** group, click **Lines**.
    

    > [!NOTE]
    > <P>The <STRONG>Lines</STRONG> button is available only if <STRONG>Formula</STRONG> or <STRONG>Planning item</STRONG> is selected in the <STRONG>Production type</STRONG> field on the <STRONG>Engineer</STRONG> FastTab for the released product.</P>



7.  In the **Formula line** form, click **New** to create a formula.

8.  In the **Formula** field, select the identification code of a formula. For more information, see [Create a formula and formula version](create-a-formula-and-formula-version.md)

9.  In the lower pane, click **New** to add an ingredient.

10. In the **Item number** field, select the identification code of an item for which you have assigned batch attributes. For more information, see [Add a batch attribute to an item](add-a-batch-attribute-to-an-item.md) and [Add a batch attribute group to an item](add-a-batch-attribute-group-to-an-item.md).

11. Click the **Setup** tab, and then select the **Inherit batch attributes to end item** check box to indicate that the batch attributes of the ingredient are inherited by the finished item.
    

    > [!NOTE]
    > <P>This check box is available if you select an item for which batch attributes are already set up in the <STRONG>Product specific</STRONG> form.</P>



12. Select the **Inherit batch attributes to co-product** check box to indicate that the batch attributes of the co-product are inherited by the finished item.
    

    > [!NOTE]
    > <P>This check box is available if you select a formula version that contains co-products in the <STRONG>Formula</STRONG> field.</P>



## Activate formula ingredients for batch attribute inheritance

Use this procedure to select the batch attribute of the ingredients that are updated for finished items.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the released product for which you have created a formula line with ingredients that have batch attributes. For more information, see Configure formula ingredients for batch attribute inheritance

3.  In the **Released product details** form, on the **Action Pane**, click the **Engineer** tab, and then in the **Formula** group, click **Lines**.

4.  In the lower pane, click **Batch attribute selection** to open the **Batch attribute selection** form. The batch attributes for all the ingredients for which the **Inherit batch attributes to end item** or **Inherit batch attributes to co-product** check box is selected are available.

5.  Select the **Active** check box to activate a batch attribute of an ingredient.
    

    > [!NOTE]
    > <P>You cannot select the <STRONG>Active</STRONG> check box for the same batch attribute more than one time.</P>



6.  Close the form.

7.  In the **Formula line** form, click **Approve**, and then click **OK** to approve the formula version.

8.  Click **Activation**, and then click **OK** to activate the formula version.

## Review formula ingredients for batch attribute inheritance

You can review the formula ingredients and batch attributes that are associated with a released product in the **Batch attribute selection** form. You can activate and deactivate batch attributes.


> [!NOTE]
> <P>If you deactivate batch attributes or activate other batch attributes, you must approve and activate the formula version again.</P>



## See also

[Formula line (form)](https://technet.microsoft.com/en-us/library/hh352331\(v=ax.60\))

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[(PM) Batch attribute selection (form)](https://technet.microsoft.com/en-us/library/jj838761\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

