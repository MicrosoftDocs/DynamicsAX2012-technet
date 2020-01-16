---
title: Create a product model
TOCTitle: Create a product model
ms:assetid: fd88012a-4cf3-4d43-a420-7d8475750fd2
ms:mtpsurl: https://technet.microsoft.com/library/Aa573438(v=AX.60)
ms:contentKeyID: 36060110
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product builder
- create a product model
audience: Application User
ms.search.region: Global
---

# Create a product model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product models are created in almost the same manner as standard bills of materials and standard routes. The product model is displayed in the upper part of the Product model form. Use the lower part to specify the items for which the selected product model should be valid. You can create models manually or use the Product model wizard.


> [!NOTE]
> <P>This information applies only to Product builder.</P>




> [!NOTE]
> <P>For more information about using the Product model wizard, see <A href="https://technet.microsoft.com/library/aa498534(v=ax.60)">Product Model Wizard (form)</A>.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. On the **Action Pane**, click the **Models** tab. In the **New** group, click **Product model**.

2.  In the upper pane, press CTRL+N to create a new line.

3.  In the **Name** field, type a unique name for the product model.

4.  You can select an item group for the product model in the **Item group** field.
    
    If you do this, the items of the selected group will be shown on a separate tab when looking up items to attach to the current product model.

5.  Click **Approve** to approve the product model.
    
    The **Approved by** field will be filled in automatically with the initials of the selected approver, and the **Approved** check box will be selected. To remove the approval, select the **Remove approval** check box in the form that appears after you click **Approve**.

6.  In the lower pane, press CTRL+N to create a new line.

7.  Select the item number for which the current product model will be valid in the **Item number** field. If the product model is valid for more than one item, select the additional items here.

8.  In the **From date** and **To date** fields, specify the first and last date when the specified item will be configurable with the current product model.

9.  Select the **Active** check box to make the product model active for the current item. A product model can be active for several items at the same time, but an item cannot have more than one active product model at the same time.

10. Click **Approve** to approve the product model version.
    
    The **Approved by** field will be filled in automatically with the initials of the selected approver, and the **Approved** check box will be selected.
    
    To remove the approval, select the **Remove approval** check box in the form that appears after you click **Approve**.
    

    > [!NOTE]
    > <P>If you have not approved the product model and clicked <STRONG>Approve</STRONG> in the lower pane, you can approve the model that the item is being attached to from this form. Select the <STRONG>Approve the product model?</STRONG> check box to approve the item.</P>



## See also

[Product model (form)](https://technet.microsoft.com/library/aa574919\(v=ax.60\))

  


