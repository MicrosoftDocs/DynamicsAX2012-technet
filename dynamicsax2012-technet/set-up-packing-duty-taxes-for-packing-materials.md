---
title: Set up packing duty taxes for packing materials
TOCTitle: Set up packing duty taxes for packing materials
ms:assetid: cdb60297-cf78-441f-8531-9ad66d90542a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn186221(v=AX.60)
ms:contentKeyID: 52250231
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- duty tax
- packing tax
- packing duty
---

# Set up packing duty taxes for packing materials 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up a packing duty tax, which is a tax that is associated with packing materials that are used to transport products. To set up a packing duty tax, you must complete these tasks, which are described in the procedures that follow:

1.  Select the **Calculate packing material fees** parameter.

2.  Set up a sales tax code as a packing duty.

3.  Create an item sales tax group.

4.  Add the sales tax code to the code for the item sales tax group.

5.  Create a packing group.

6.  Create a packing material.

7.  Create a packing unit.

8.  Create a packing material fee.

9.  Add the packing group to the product.

## Select the Calculate packing material fees parameter

Select the **Calculate packing material fees** check box in the **Inventory and warehouse management parameters** form to indicate that your legal entity collects or reports packing material fees.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Select the **Calculate packing material fees** check box.

## Set up sales tax information

To set up sales tax information, you must create codes for the sales tax and the item sales tax group. Then you must add the sales tax code to the code for the item sales tax group.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a sales tax code. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

3.  On the **Calculation** FastTab, in the **Origin** field, select **Amount per unit**.

4.  In the **Unit** field, select the unit that the purchase duty is calculated for. This is also the unit that is used in the calculation of the amount per unit.

5.  To define the amount of sales tax per unit, click **Values**. For more information, see [Values of sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa500790\(v=ax.60\)). Close the **Values** form when you have finished.

6.  Select the **Packing duty** check box.

7.  Close the **Sales tax codes** form.

8.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

9.  Create an item sales tax group. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

10. On the **Setup** FastTab, click **Add**, and then select the sales tax code that you created in step 2.

## Set up information about packing materials

After you create packing groups, packing material codes, packing units, and packing material fees, you can assign them to items. When you create packing material codes, packing units, and packing material fee codes, you must select the same unit that you selected in the **Sales tax codes** form.

1.  Click **Inventory management** \> **Setup** \> **Packing material** \> **Packing groups**.

2.  Create a packing group. For more information, see [Create packing groups](create-packing-groups.md).

3.  Close the **Packing groups** form.

4.  Click **Inventory management** \> **Setup** \> **Packing material** \> **Packing material codes**.

5.  Create a packing material code and select the same unit that you selected in the **Sales tax codes** form. For more information, see [Create packing material codes](create-packing-material-codes.md).

6.  Close the **Packing material codes** form.

7.  Click **Inventory management** \> **Setup** \> **Packing material** \> **Packing units**.

8.  Click **New**. In the **Item code** field, select **All**.

9.  Select the same unit that you selected in the **Sales tax codes** form and the **Packing material codes** form.

10. On the **Packing material** FastTab, select the code that you created in step 5.

11. Close the **Packing units** form.

12. Click **Inventory management** \> **Setup** \> **Packing material** \> **Packing material fees**.

13. Create a packing material fee code and select the same unit that you selected in the **Sales tax codes** form. For more information, see [Define packing material fees](define-packing-material-fees.md).

14. Close the **Packing material fees** form.

15. Click **Product information management** \> **Common** \> **Released products**.

16. Select the product name to assign a packing group to.

17. On the **Action Pane**, click **Edit**.

18. On the **Manage inventory** FastTab, in the **Packing group** field, select a packing group.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

