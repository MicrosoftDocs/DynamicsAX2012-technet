---
title: (IND) Create and post a purchase order line with a negative quantity for an item that is not inventoried
TOCTitle: (IND) Create and post a purchase order line with a negative quantity for an item that is not inventoried
ms:assetid: ff303a59-2081-4bb3-894e-44d08a0b1535
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710991(v=AX.60)
ms:contentKeyID: 49386403
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- order
- purchase
- India
- IND
- noninventoried
- quanity
audience: Application User
ms.search.region: India
---

# (IND) Create and post a purchase order line with a negative quantity for an item that is not inventoried 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a new or existing purchase order, you can add a purchase order line that has a negative quantity for an item that is not inventoried. You can also create and post a sales return order for an item that is not inventoried. Only indirect taxes can be calculated on negative purchase or sales order lines.

In the same or a new order, you can also add a line that has a negative quantity for an item that is not stocked. All taxes that are attached to the negative quantity lines for the items that are not stocked must be calculated, updated, and accounted for in the same way that the inventoried items that have a negative quantity are.

The quantity fields in the purchase order form enable the calculation of the ordered quantity. The quantity is used to calculate the currency amounts that are passed to the purchase order line accounting distribution. They are also used to retain the ordered quantity for the correct calculation of vendor delivery. The quantity fields on the packing slip journal line support the accounting distribution matching between the purchase order line and the packing slip journal line. Matching the accounting distribution requires the introduction of quantity variances on the purchase order line and on the purchase packing slip journal line.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select the purchase order to update, and then, on the **Action Pane**, on the **Purchase order** tab, click **Edit**.

2.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open **Vendor invoice** form, and then specify the **Invoice number**. Close the form.

3.  In the **Purchase order** form, on the **Action Pane**, on the **Invoice** tab, in the **History** group, click **Invoice**.

4.  In the **Invoice journal** form, click **Voucher**.

5.  For the positive quantity, verify the voucher entries as VAT recoverable. Credit the negative quantity to VAT payable.


> [!NOTE]
> <P>When you post a purchase order that has a negative quantity, indirect taxes are calculated.</P>


  


