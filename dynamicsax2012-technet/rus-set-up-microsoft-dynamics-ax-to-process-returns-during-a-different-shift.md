---
title: (RUS) Set up Microsoft Dynamics AX to process returns during a different shift
TOCTitle: (RUS) Set up Microsoft Dynamics AX to process returns during a different shift
ms:assetid: f7c543b8-a605-41a1-b2df-b50cdfa0cffe
ms:mtpsurl: https://technet.microsoft.com/library/Dn716025(v=AX.60)
ms:contentKeyID: 62200279
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailParameters
- Forms.RetailStoreTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up Microsoft Dynamics AX to process returns during a different shift 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up Microsoft Dynamics AX to process return transactions for items that are returned during a shift that is different from the shift in which the items are sold at the point of sale (POS).

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
<td><p>Microsoft Dynamics AX 2012 R2 or AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>In the <strong>Retail parameters</strong> form, in the <strong>Posting</strong> area, on the <strong>Payments</strong> FastTab, in the <strong>Cash payment journal</strong> field, set up the default cash payment journal to post cash payments.</p></li>
<li><p>Create a permission group to process return transactions during a different shift by selecting <strong>Warn for return</strong> or <strong>Allow return</strong> in the <strong>Return during a different shift</strong> field in the <strong>Permission groups</strong> form. Assign the permission group to the cashier worker record. For more information, see <a href="rus-set-up-permission-groups-to-regulate-the-return-of-sold-items.md">(RUS) Set up permission groups to regulate the return of sold items</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Set up a cash office in a store

Use this procedure to set up a cash account that is used as a cash office in a store. You cannot delete a cash account that is used as a cash office in a store.

To perform this task, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  Select a retail store, and then click **Edit**, or create a retail store. For more information about how to create a retail store, see [Set up a retail store](set-up-a-retail-store.md).

3.  On the **General** FastTab, in the **Cash office** field, select a cash account to be used as a cash office for the selected retail store.

## Optional: Set up the parameter to process return transactions during a different shift in the same way that you process return transactions during the same shift

Use this procedure to set up parameters to process return transactions during a different shift in the same way that you process return transactions during the same shift.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Select the **Process as a return in the same shift** check box to process return transactions during a different shift in the same way that you process return transactions during the same shift.
    

    > [!NOTE]
    > <P>You must clear the <STRONG>Process as a return in the same shift</STRONG> check box to process return transactions by specifying the disbursement slip number or by automatically creating a disbursement slip at the POS. When you clear this check box, a fiscal receipt is not generated for the return transaction that is performed during a different shift.</P>



## Related tasks

[(RUS) Verify the details of a disbursement slip that is automatically created for a cash return transaction](rus-verify-the-details-of-a-disbursement-slip-that-is-automatically-created-for-a-cash-return-transaction.md)

[(RUS) Post a statement for return transactions that are processed during a different shift](rus-post-a-statement-for-return-transactions-that-are-processed-during-a-different-shift.md)

[(RUS) Set up the refund payment method control](rus-set-up-the-refund-payment-method-control.md)

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

  


