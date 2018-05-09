---
title: Add co-products or by-products to a batch order
TOCTitle: Add co-products or by-products to a batch order
ms:assetid: 23d83378-020d-4c7a-827d-bb4f9221b2b1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352188(v=AX.60)
ms:contentKeyID: 36687821
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- add by-products
- add by-products to batch orders
- add co-products
- add co-products to batch orders
- by-products
- co-products
---

# Add co-products or by-products to a batch order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the status of a batch order is **Created**, you can add a new co-product or by-product to the order by using the **Co-Products** form. If the **Co-product variations** check box is selected in the **Batch order** form, you can report co-products and by-products as finished. You can do this regardless of whether the co-products or by-products are associated with the batch order formula.

## Add a co-product or by-product to a batch order

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Select a batch order that has the status of **Created**.

3.  Double-click the batch order to open the **Batch order** form.

4.  On the **Action Pane**, on the **Production order** tab, in the **Order details** group, click **Co-products**. The **Co-products-batch** form is displayed.

5.  Press CTRL+N to add a new co-product or by-product line to the batch order.

6.  In the **Item number** field, select the co-product or by-product that you want to add.

7.  In the **Quantity** or **CW quantity** field, enter the quantity of the co-product or by-product that is expected to be produced.

8.  Optionally, you can enter or change the remaining information.

## Report a co-product or by-product that is not associated with the batch order

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Select a batch order that has the status of **Started**.

3.  On the **Setup** FastTab of the **Batch order** form, verify that **Co-products variations** is selected.

4.  On the **Action Pane**, on the **Production order** tab, in the **Process** group, click **Report as finished**. The **Report as finished** form is displayed.

5.  On the **Action Pane**, on the **Production order** tab, in the **Order details** group, click **Co-products**. The **Co-products** form is displayed.

6.  Press CTRL+N to add a new co-product or by-product line to the **Report as finished** form.

7.  In the **Item number** field, select the co-product or by-product that you want to add.

8.  In the **Quantity** or **CW quantity** field, enter the quantity of the co-product or by-product that is expected to be produced.

9.  Click **OK** to confirm.

10. Optionally, you can enter or change the remaining information.

## See also

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

[Co-products (form)](https://technet.microsoft.com/en-us/library/hh328754\(v=ax.60\))

[Co/By products - batch (form)](https://technet.microsoft.com/en-us/library/hh328643\(v=ax.60\))

[Report as finished-batch orders (form)](https://technet.microsoft.com/en-us/library/hh328602\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

