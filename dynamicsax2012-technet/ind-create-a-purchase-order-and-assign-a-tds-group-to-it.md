---
title: (IND) Create a purchase order and assign a TDS group to it
TOCTitle: (IND) Create a purchase order with TDS
ms:assetid: 7faa8321-b7bd-44be-8a18-ea107190b9cc
ms:mtpsurl: https://technet.microsoft.com/library/JJ677984(v=AX.60)
ms:contentKeyID: 49385948
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a purchase order and assign a TDS group to it 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate the tax deducted at source (TDS) for a purchase order by assigning a TDS group to the purchase order.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  In the **Create purchase order** form, enter information about the purchase order. For more information, see [Create a purchase order](create-a-purchase-order.md).

3.  In the **Purchase order** form, on the **Purchase order lines** FastTab, click **Add line**, and then, in the **Item number** field, select the item.
    
    You can create or modify the product type in the Product form.

4.  In the **Quantity**, **Unit**, and **Unit price** fields, enter the quantity ordered, the unit of measure for the item, and the purchase price per unit. The net amount, including any discount, is displayed in the **Net amount** field.

5.  On the **Line details** FastTab, on the **Setup** tab, in the **TDS group** field, select the TDS group for calculating withholding tax.

6.  On the **Purchase order lines** FastTab, click **Withholding tax**.

7.  In the **Temporary withholding tax transactions** form, in the **Adjusted withholding tax amount in total** field, verify the calculated TDS amount, and then close the form.

After the purchase order is posted, you can view the following details:

  - The posted voucher details, in the **Voucher transactions** form
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase** tab, in the **Accounting** group, click **Vouchers**.

  - The TDS rate applied, in the **Percent** field in the **Withholding tax transactions** form
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase** tab, in the **Accounting** group, click **Vouchers** \> **Posted withholding tax**.

  - The invoice or payment amount and the TDS amount in the current currency, in the **Amount origin** and **TDS** fields in the **Vendor transactions** form
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, click **Transactions**.

## See also

[(IND) Vendor transactions (modified form)](https://technet.microsoft.com/library/jj664503\(v=ax.60\))

[(IND) Adjust a TDS or TCS value](https://technet.microsoft.com/library/jj664585\(v=ax.60\))

  


