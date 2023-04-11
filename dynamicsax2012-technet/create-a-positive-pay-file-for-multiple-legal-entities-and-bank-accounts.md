---
title: Create a positive pay file for multiple legal entities and bank accounts
TOCTitle: Create a positive pay file for multiple legal entities and bank accounts
ms:assetid: 61a15898-7bf4-4f53-95ae-2475bf5c3c71
ms:mtpsurl: https://technet.microsoft.com/library/Dn269116(v=AX.60)
ms:contentKeyID: 54920068
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.BankPositivePaySummary
- MsDynAx060.Forms.BankPositivePaySummary
audience: Application User
ms.search.region: Global
---

# Create a positive pay file for multiple legal entities and bank accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to generate a positive pay file for multiple legal entities and bank accounts, confirm a positive pay file, and recall a positive pay file.

You can use positive pay to generate an electronic list of checks that is provided to the bank. When the check is presented to the bank, the bank compares the check with the list of checks. If the check matches what the bank has on file in the list, the bank clears the check. If there is a difference, the bank holds the check for review.

For information about creating, confirming and recalling positive pay files for payroll, see [Issue worker payments](issue-worker-payments.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



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
<td><p>Set up</p></td>
<td><p><a href="set-up-positive-pay.md">Set up positive pay</a></p></td>
</tr>
</tbody>
</table>


## 1\. Generate a positive pay file for multiple legal entities and bank accounts

You can generate a positive pay file for a single legal entity and a single bank account by using the **Bank accounts** form. For more information, see [Generate and print vendor checks](generate-and-print-vendor-checks.md). To generate positive pay files for multiple legal entities and bank accounts at the same time, use the information in this procedure, instead.

To generate a positive pay file for multiple legal entities and bank accounts, follow these steps:

1.  Click **Cash and bank management** \> **Periodic** \> **Positive pay file**.

2.  Select the positive pay format for the file.

3.  Select whether to generate the positive pay file for all legal entities or for a selected legal entity. If necessary, select a legal entity.

4.  Select whether to generate the positive pay file for all bank accounts that use the format that you specified in step 2, or for a selected bank account. If necessary, select a bank account. If you select all bank accounts, it is possible that only one positive pay file will be generated. In most cases, it is best to generate positive pay files for one bank account at a time if multiple bank accounts share the same positive pay format.

5.  In the **Cut-off date** field, enter the last check date to include in the positive pay file. All checks that haven’t been included in a positive pay file through this check date are included in the file.

6.  Click **OK**.

## 2\. Confirm a positive pay file

After the checks that are listed in a positive pay file have been paid, you receive a confirmation number from your bank. Then, you can confirm the positive pay file in Microsoft Dynamics AX. Confirming a positive pay file records the confirmation number that you receive from the bank.

To confirm a positive pay file, follow these steps:

1.  Click **Cash and bank management** \> **Inquiries** \> **Positive pay file summary**.

2.  Select a positive pay file that has a status of **Created**.

3.  Click **Confirmation**.

4.  Enter the confirmation number that you received from the bank.

5.  Click **OK**.

## 3\. If required: Recall a positive pay file

If you have to change a positive pay file, you can recall it. Recalling a positive pay file resets the field for each check that indicates whether the check has been included in a positive pay file. Then, you can create a new positive pay file that includes the check that was recalled.

To recall a positive pay file, follow these steps:

1.  Click **Cash and bank management** \> **Inquiries** \> **Positive pay file summary**.

2.  Select a positive pay file that has a status of **Created**.

3.  Click **Recall**. A message confirms that the recall process was successful.

## Related tasks

[Generate and print vendor checks](generate-and-print-vendor-checks.md)

[Issue worker payments](issue-worker-payments.md)

[Void unposted checks](void-unposted-checks.md)

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
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a positive pay file for multiple legal entities and bank accounts, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain bank positive pay information</strong></p></td>
<td><p>BankPositivePayProcess</p></td>
<td><p>Generate positive pay files for multiple legal entities and bank accounts.</p></td>
</tr>
<tr class="even">
<td><p><strong>View bank positive pay information for multiple legal entities</strong></p></td>
<td><p>BankPositivePayView</p></td>
<td><p>View positive pay files in the <strong>Positive pay file summary</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Confirm positive payment file</strong></p></td>
<td><p>BankPositivePayConfirm</p></td>
<td><p>Confirm positive pay files.</p></td>
</tr>
<tr class="even">
<td><p><strong>Recall positive pay file</strong></p></td>
<td><p>BankPositivePayRecall</p></td>
<td><p>Recall positive pay files.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


