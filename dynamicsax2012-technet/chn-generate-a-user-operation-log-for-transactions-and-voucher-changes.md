---
title: (CHN) Generate a user operation log for transactions and voucher changes
TOCTitle: (CHN) Generate a user operation log for transactions and voucher changes
ms:assetid: adc4b036-601e-4434-9000-563f934b5471
ms:mtpsurl: https://technet.microsoft.com/library/Dn864770(v=AX.60)
ms:contentKeyID: 63400917
author: tonyafehr
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- transactions
- vouchers
- operation type
- Forms.ComplianceUserOperationLogConfig_CN
- operation date
- user name
- user operation log
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Generate a user operation log for transactions and voucher changes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to generate a user operation log by setting up an operation type, operation date, or user names as criteria. Based on the criteria, Microsoft Dynamics AX tracks and records user operations in a log, including the type of operation, the user name, and the time and date when you modify transactions and vouchers for a document such as a sales order.

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with cumulative update 8 (CU8)</p></td>
</tr>
<tr class="even">
<td><p>Related setup tasks</p></td>
<td><p></p>
<ol>
<li><p>Create a new user in the <strong>Users</strong> form. For more information, see <a href="create-new-users-in-microsoft-dynamics-ax.md">Create new users in Microsoft Dynamics AX</a>.</p></li>
<li><p>Set up types of operations for tables to track and log the user operations in the <strong>Database log setup</strong> form. For more information, see <a href="configure-and-manage-database-logging.md">Configure and manage database logging</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


To set up parameters and to generate a user operation log, follow these steps:

1.  Click **System administration** \> **Reports** \> **Database** \> **User operation log inquiry**.

2.  In the **By operation type** field, select a table ID check box to track the user operation.

3.  In the **User** field, specify a user name or user names to record user operations for transactions and voucher changes.

4.  Specify a from date and a to date to record the user operation for the specified time period, and then click **OK** to open the **User operation log** form.

5.  Optional: On the **Batch** tab, specify batch job details to generate the user operation log for the specified criteria.

## Next step

You can clean the user log files. For more information, see [Clean up user logs](clean-up-user-logs.md).

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>Database log</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the IT manager role.</p></td>
</tr>
</tbody>
</table>

  


