---
title: (BRA, MEX) Set up General ledger to reverse and update opposite sign amounts
TOCTitle: (BRA, MEX) Set up General ledger to reverse and update opposite sign amounts
ms:assetid: 53b704ea-8fdb-4f90-a51c-6adae5e6f48b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497721(v=AX.60)
ms:contentKeyID: 62200235
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sign
- Mexico
- Brazil
- negative credit
- negative credits
- negative debit
- opposite
- negative debits
- opposites
- signs
- opposite amounts
- opposite signs
- opposite sign
- opposite amount
audience: Application User
ms.search.region: Brazil
---

# (BRA, MEX) Set up General ledger to reverse and update opposite sign amounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to post negative debit amounts as credits, and negative credit amounts as debits. It also describes how to verify and update negative debit or credit amounts that already exist in posted transactions in the general ledger.

Brazilian and Mexican government reporting requires that negative debit amounts be displayed in the credit column of the reports, and negative credit amounts be displayed in the debit column. You can use the **General ledger parameters** form to select the **Reverse opposite sign amounts** parameter to enable this functionality. When the parameter is selected, if you post a negative debit amount, it becomes a credit. If you post a negative credit amount, it becomes a debit.

You can then run the update process to verify whether negative debit amounts or negative credit amounts already exist in posted journal transactions in the general ledger. The update process reverses the sign so that negative debit amounts become credits, and negative credit amounts become debits.

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
<td><p>Related module configuration</p></td>
<td><p>Clear the <strong>Correction</strong> check box in the <strong>General ledger parameters</strong> form so that debit transactions aren’t reversed by adding a negative debit amount, and credit transactions aren’t reversed by adding a negative credit amount.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(BRA, MEX) The primary address for the legal entity must be in the following countries/regions: Brazil or Mexico.</p></td>
</tr>
</tbody>
</table>


## 1\. Enable reverse opposite sign amounts

Use the **General ledger parameters** form to enable the **Reverse opposite sign amounts** parameter so that when you post a negative debit amount in the general ledger, it becomes a credit, and when you post a negative credit amount, it becomes a debit.

To set up **General ledger parameters** to reverse opposite sign amount transactions, follow these steps:

1.  Switch to the legal entity that you are enabling the parameter for.

2.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

3.  On the **Accounting rules** FastTab, in the **Accounting rules to use** area, select the **Reverse opposite sign amounts** check box.

## 2\. Update opposite sign amounts for existing transactions

When you enable the **Reverse opposite sign amounts** parameter, the functionality applies to amounts that are entered after the parameter is enabled, and to saved transaction amounts.

However, you can verify whether negative debit or credit amounts already exist in posted journal transactions in the general ledger, and then reverse the sign so that negative debit amounts become credits and negative credit amounts become debits.

To find and update existing transactions in the general ledger, follow these steps:

1.  Switch to the legal entity that includes the transaction that you’re updating.

2.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

3.  On the **Accounting rules** FastTab, in the **Accounting rules to use** area, verify that the **Reverse opposite sign amounts** check box is selected.

4.  On the **Accounting rules** FastTab, click the **Update opposite sign amounts** button.
    
    The following message is displayed: **Are you sure that you want to update the transactions with opposite sign amounts?**

5.  Click **OK**. The **Update opposite sign amounts** form opens.

6.  On the **General** tab, enter the date range for the transactions to include in the update process. All transactions that have transaction dates within this range will be updated.

7.  Optional: Click the **Batch** tab to select options for running the update process as a batch job. For more information about batch processing, see [Batch processing overview](batch-processing-overview.md).

8.  Click **OK**.

## 3\. Optional: View the effect of updating opposite sign amount transactions

Complete this procedure if you want to see the effect that the **Update opposite sign amounts** process has on general ledger transactions.

You can view the effect of the update process on general ledger transactions in multiple ways, such as those described in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Description</p></th>
<th><p>For more information, see …</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate a <strong>Detailed trial balance</strong> report. Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Detailed trial balance</strong>.</p></td>
<td><p>Displays opening balances, debits, credits, and the resulting balances for ledger accounts for a specified date range.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=390497%26clcid=0x409">Trial balance report (LedgerTrialBalance)</a></p></td>
</tr>
<tr class="even">
<td><p>View the General ledger <strong>Voucher transactions</strong> inquiry form. Click <strong>General ledger</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Voucher transactions</strong>.</p></td>
<td><p>Displays the ledger transactions in chronological order.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View the <strong>Trial balance</strong> list page. Click <strong>General ledger</strong> &gt; <strong>Common</strong> &gt; <strong>Trial balance</strong>.</p></td>
<td><p>Lets you view and take action on the trial balance list.</p></td>
<td><p><a href="list-pages.md">List pages</a></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>These are only some of the ways you can report on and view general ledger transactions. To print financial reports, you can use Management Reporter for Microsoft Dynamics ERP, or you can use the traditional financial reports that are included with Microsoft Dynamics AX. For more information about how to print financial reports by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>



The following tables show an example of the effect of updating opposite sign amounts in the general ledger.

**Posted transactions in the general ledger before the update process was run**

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Entry type</p></th>
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
<th><p>Update required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Original entry</p></td>
<td><p>110180</p></td>
<td><p>250.66</p></td>
<td><p></p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Original entry</p></td>
<td><p>250200</p></td>
<td><p></p></td>
<td><p>250.66</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Reversing entry</p></td>
<td><p>110180</p></td>
<td><p>-250.66</p></td>
<td><p></p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Reversing entry</p></td>
<td><p>250200</p></td>
<td><p></p></td>
<td><p>-250.66</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


**Posted transactions in the general ledger after the update process was run**

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Entry type</p></th>
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
<th><p>Update required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Original entry</p></td>
<td><p>110180</p></td>
<td><p>250.66</p></td>
<td><p></p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Original entry</p></td>
<td><p>250200</p></td>
<td><p></p></td>
<td><p>250.66</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Reversing entry</p></td>
<td><p>110180</p></td>
<td><p></p></td>
<td><p>250.66</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Reversing entry</p></td>
<td><p>250200</p></td>
<td><p>250.66</p></td>
<td><p></p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


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
<td><p>Not applicable</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Not applicable</p></td>
</tr>
</tbody>
</table>

  


