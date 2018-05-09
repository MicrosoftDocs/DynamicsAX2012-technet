---
title: (THA, SAU, GBR, IRL) Set up a withholding tax group and attach it to a vendor or customer
TOCTitle: (THA, SAU, GBR, IRL) Set up a withholding tax group and attach it to a vendor or customer
ms:assetid: d3d81746-583d-4e35-b564-8afe5bc23332
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242926(v=AX.60)
ms:contentKeyID: 36059515
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Thailand
- vendors
- withholding tax group
---

# (THA, SAU, GBR, IRL) Set up a withholding tax group and attach it to a vendor or customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Withholding tax groups** form to create a withholding tax group. After you create a group, you can assign multiple withholding tax codes and calculate multiple withholding tax rates for transactions. You can also attach a withholding tax group to a vendor or customer. For more information, see [Withholding tax groups (form)](https://technet.microsoft.com/en-us/library/aa591973\(v=ax.60\)).

## Create a withholding tax group

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax groups**.

2.  Press CTRL+N to create a new withholding tax group.

3.  In the **Withholding tax group** field, enter the identification of the group.

4.  In the **Description** field, enter a description of the group.

5.  On the **Setup** FastTab, in the **Withholding tax code** field, select a withholding tax code to attach to the group. You can create new lines and attach multiple codes to the group.

## Attach the withholding tax group to a vendor and a customer

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor, and on the **Action Pane**, click **Edit** to open the **Vendors** form.

3.  On the **Invoice and delivery** FastTab, select the **Calculate withholding tax** check box to calculate the withholding tax for vendor payment transactions.

4.  In the **Withholding tax group** field, select the withholding tax group and attach it to the vendor.

5.  In the **Vendor type** field, select the type of vendor.

6.  Close the form to save your changes.

7.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

8.  Select a customer and then click **Edit** to open the **Customers** form.

9.  Click the **Invoice and delivery** FastTab and select the **Calculate withholding tax** check box to calculate the withholding tax for customer payment transactions.

10. In the **Withholding tax group** field, select the withholding tax group and attach it to the customer.

11. Close the form to save your changes.

## See also

[Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

[Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\))

[Withholding tax codes (form)](https://technet.microsoft.com/en-us/library/aa585361\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

