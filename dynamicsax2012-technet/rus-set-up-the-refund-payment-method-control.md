---
title: (RUS) Set up the refund payment method control
TOCTitle: (RUS) Set up the refund payment method control
ms:assetid: 863fb5e7-b643-4ffe-9b52-6342474e7670
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621056(v=AX.60)
ms:contentKeyID: 62200271
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Retail
- Forms.HcmWorkerListPage
- Forms.RetailParameters
- Forms.RetailPosPermissionGroup
- Forms.RetailPositionPosPermission
- Russia
- RUS
- payment method control
- Refund payment
- Refund payments
---

# (RUS) Set up the refund payment method control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the refund payment method control in Microsoft Dynamics AX to process refunds using the following payment methods at the retail point of sale (POS):

  - The same payment method as the one that was used for the original transaction

  - A payment method other than the one that was used for the original transaction

Follow the steps in this topic to set up a permission group to return items using payment methods other than the ones that were used in the original transactions and set up Microsoft Dynamics AX for Retail POS to initialize refund amounts.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Retail in AX 2012 R2 or AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
</tbody>
</table>


## Set up a permission group to return items using payment methods other than the ones that were used in the original transactions

Use this procedure to set up a permission group to return items using payment methods other than the ones that were used in the original transactions. You can then assign the permission group to a worker who uses POS.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Permission groups**.

2.  Click **New** or press CTRL+N to create a permission group. For more information, see [(RUS) Set up permission groups to regulate the return of sold items](rus-set-up-permission-groups-to-regulate-the-return-of-sold-items.md) and [Permission groups (form)](https://technet.microsoft.com/en-us/library/hh597270\(v=ax.60\)).

3.  On the **Permissions** FastTab, select the **Allow refunds using different methods** check box to allow the return of items using payment methods other than the one that was used in the original transaction.

4.  Close the **Permission groups** form.

5.  Click **Retail** \> **Common** \> **Workers**.

6.  Select a worker, and then on the **Action Pane**, on the **Retail** tab, in the **Set up** group, click **POS permissions**.

7.  Select the **Override permissions** check box to override the permissions for the worker.

8.  In the **POS permission group** field, select the permission group that you created.

## Set up Retail POS to initialize refund amounts

Use this procedure to set up the parameter to initialize refund amounts based on payment methods at the POS.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Select the **Initialize refund amounts** check box.

## Related tasks

[Set up retail products](set-up-retail-products.md)

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

[View retail sales](view-retail-sales.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

