---
title: Create a letter of guarantee request for a purchase order
TOCTitle: Create a letter of guarantee request for a purchase order
ms:assetid: ef3bfdbe-a3a9-472b-90c0-41f5211304d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227505(v=AX.60)
ms:contentKeyID: 36059918
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Create the letter of guarantee request for a purchase order
- Letter of guarantee request for purchase order
---

# Create a letter of guarantee request for a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A letter of guarantee can be issued for a purchase order transaction between a principal and a beneficiary. After the purchase order is created, the principal can create a letter of guarantee request for the vendor and submit it to the bank. When the bank approves the request, the letter of guarantee is issued to the beneficiary. For more information, see [About letter of guarantee](about-letter-of-guarantee.md) and [Activate the letter of guarantee](activate-the-letter-of-guarantee.md).

## Create a purchase order

Use the **Create purchase order** form to create a purchase order with the **Bank document type** as **Letter of guarantee**.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Click **Purchase order** to create a new purchase order.

3.  In the **Create purchase order** form, select the **One-time supplier** check box for a new supplier that you do not expect to place future orders with.

4.  In the **Vendor account** field, select the vendor that requested the letter of guarantee.

5.  Click the **General** FastTab, and in the **Bank document type** field, select **Letter of guarantee**. Enter any other required details.

6.  Click **OK** to close the **Create purchase order** form and return to the **Purchase order** form.

## Create a letter of guarantee request for a purchase order

You can request a letter of guarantee for a vendor using the **Purchase order** form. After you make a request, you must submit the request to the bank for approval.

1.  In the **Purchase order** form, click the **Purchase order lines** FastTab.

2.  Click **Add line** to create a purchase order line for the created purchase order and specify item details in the **Item number**, **Quantity**, and **Unit price** fields.

3.  On the Action Pane, click the **Manage** tab.

4.  In the **Bank document** group, click **Letter of guarantee** to open the **Letter of guarantee** form. For information about how to create the request, submit the request to the bank, and issue the letter of guarantee to the beneficiary, see [Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md).

5.  Close the forms to save your changes.

## See also

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

