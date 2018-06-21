---
title: Clean up closed and unused on-hand inventory transactions
TOCTitle: Clean up closed and unused on-hand inventory transactions
ms:assetid: ae110aff-7aaf-4553-bd49-868b47e0caf2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn505749(v=AX.60)
ms:contentKeyID: 59604023
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SysOperationTemplateForm
---

# Clean up closed and unused on-hand inventory transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



This procedure describes how to delete closed and unused entries for on-hand inventory that is assigned to one or more tracking dimensions. Closed transactions contain the value of zero for all quantities and cost values, and are marked as closed. Deleting these transactions can improve the performance of queries for on-hand inventory. Transactions will not be deleted for on-hand inventory that is not assigned to tracking dimensions.


> [!WARNING]
> <P>If you have implemented customizations in Microsoft Dynamics AX that use on-hand inventory transactions, you should carefully consider whether to delete these transactions.</P>



## Delete entries for on-hand inventory

To delete entries for serialized on-hand inventory, follow these steps:

1.  **Inventory management** \> **Periodic** \> **Clean up** \> **On-hand entries cleanup**

2.  Optional: In the **Delete if not updated for this many days** field, enter the number of days in which entries have been unchanged. Entries that have been changed during this period are not deleted.

3.  Click **OK**.

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
<td><p><strong>License keys</strong></p></td>
<td><p><strong>Trade and logistics</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p><strong>Information technology manager</strong></p></td>
</tr>
</tbody>
</table>


## See also

[On-hand inventory (form)](https://technet.microsoft.com/en-us/library/aa616522\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

