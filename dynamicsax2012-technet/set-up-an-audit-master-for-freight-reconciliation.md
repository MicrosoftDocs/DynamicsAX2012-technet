---
title: Set up an audit master for freight reconciliation
TOCTitle: Set up an audit master for freight reconciliation
ms:assetid: e25f40ef-03d0-44d4-80bb-0f6ff52ceb22
ms:mtpsurl: https://technet.microsoft.com/library/Dn553206(v=AX.60)
ms:contentKeyID: 62200172
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- auditing
- automatic payment
- Forms.TMSAuditMaster
- MsDynAx060.Forms.TMSAuditMaster
- freight reconciliation
- audit tolerance level
audience: Application User
ms.search.region: Global
---

# Set up an audit master for freight reconciliation 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Use the **Audit master** form to set up the tolerance level for automatic freight bill matching. When you reconcile freight, you can match freight bills with invoices that have a specified audit tolerance level. If the values that are used for the matching process are in the specified tolerance level, the reconciliation is approved and processed for automatic payment of the invoice. You can create different audit masters for different freight bill types or carrier types.

1.  Click **Transportation management** \> **Setup** \> **Freight reconciliation** \> **Audit master**.

2.  Click **New** to create a new audit master.

3.  On the **Criteria** FastTab, enter the unique criteria for the audit master.

4.  In the **Sequence** field, enter a number to specify the order in which bills are reconciled.

5.  On the **Tolerance** FastTab, select the minimum and maximum values for audit types and tolerance levels.

6.  On the **Result** FastTab, select the reconciliation reason codes for the overage amount and the underage amount.

7.  On the **Exceptions** FastTab, create audit exceptions for the audit master.

## Related tasks

[Set up freight reconciliation parameters](set-up-freight-reconciliation-parameters.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


