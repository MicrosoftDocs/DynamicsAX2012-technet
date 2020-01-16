---
title: About changing the project group
TOCTitle: About changing the project group
ms:assetid: 4c4dbabf-0f30-4e7d-86aa-ae8b17a84591
ms:mtpsurl: https://technet.microsoft.com/library/Aa497020(v=AX.60)
ms:contentKeyID: 42117756
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- estimate project
- project group
- project type
audience: Application User
ms.search.region: Global
---

# About changing the project group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In most cases, a project is not assigned to a different project group after the project is created. If you do have to assign the project to a different group, it is typically because the circumstances of the project have changed.

**Example 1** – A customer finds that expenses on a Time and material project are much higher than expected. As a result, they insist that the project be changed to a Fixed-price project.

**Example 2** – A fixed-price project is begun as a short-term project that is not set up for WIP. Later, the project is updated so that it accrues revenue.

**Example 3** – An Internal project is converted to a project that bills a customer.

Whether the project group assignment for a project can be changed depends on multiple factors.

The remainder of this topic explains the criteria that are required to change a project group assignment. These criteria include additional steps that you might have to take before you can change the project group.


> [!NOTE]
> <P>If a project is linked to an estimate project, you cannot change the project group directly. You must change the project group of the estimate project. All projects that are linked to the estimate project are changed to the new project group.</P>



## Changing a project to the same type of project group

Your system can be set up to include multiple project groups of the same project type. For example, you might have several Fixed-price project group types, one for each of your company’s revenue recognition scenarios.

The following table shows some tasks that you may have to complete before you assign a project to another group of the same type.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project type</p></th>
<th><p>Action required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Time and material</strong> and <strong>Internal</strong></p></td>
<td><p>Reverse any WIP postings.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed-price</strong> and <strong>Investment</strong></p></td>
<td><p>Reverse all estimates and eliminations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Time</strong> and <strong>Cost</strong></p></td>
<td><p>None.</p></td>
</tr>
</tbody>
</table>


## Changing a project to a different type of project group

When you assign a project to a group that has a different project type, the following general limitations apply:

  - If the project includes transactions for hours, expenses, fees, or items, the project type can be changed only if the transaction status is **Posted** or **Adjusted**.

  - If the project includes on-account transactions, you can change the project to a group that has another on-account posting setup only if the transaction status of the on-account transactions is **Registered** or **Invoice proposal**.

  - In general, you cannot change a project to another project group type if the project contains transaction types that are not permitted for the new project type.

The following tables provide more details about the requirements for changing the project group type when the original project contains certain kinds of transactions.

In these tables, the first column indicates the type of transaction and other criteria. The remaining columns indicate whether a project can be changed to a project group of each project type.

## Hour transactions

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Hours</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Hours, if <strong>Never ledger</strong> is selected in the <strong>Post costs - hour</strong> field in the <strong>Project groups</strong> form.</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## Expense transactions

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## Item transactions

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Item</p>
<p>(Sales orders only)</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Item</p>
<p>(Purchase orders and Item requirements only)</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## Fee transactions

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fee</p>
<p>(Journals only)</p></td>
<td><p>Yes</p></td>
<td><p>Yes, if the transaction status is set to <strong>Adjusted</strong>.</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Fee</p>
<p>(Estimates only)</p></td>
<td><p>Yes, if the transaction status is set to <strong>Reversed</strong>.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Fee</p>
<p>(Subscriptions only)</p></td>
<td><p>Yes</p></td>
<td><p>Yes, if the transaction status is set to <strong>Adjusted</strong>.</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## On-account transactions

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>On-account</p>
<div class="alert">

> [!NOTE]
> <P>If deduction transactions are associated with the on-account transaction, the project group cannot be changed.</P>


</div></td>
<td><p>Yes, if the selection in the <strong>On-account invoicing</strong> field in the <strong>Project groups</strong> form is the same for both project groups.</p></td>
<td><p>Yes, if the selection in the <strong>On-account invoicing</strong> field in the <strong>Project groups</strong> form is the same for both project groups.</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>On-account</p>
<div class="alert">

> [!NOTE]
> <P>If deduction transactions are associated with the on-account transaction, the project group cannot be changed.</P>


</div></td>
<td><p>Yes, if the selection in the <strong>On-account invoicing</strong> field in the <strong>Project groups</strong> form is the same for both project groups.</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## Subscription transactions


> [!NOTE]
> <P>If a subscription is connected to the original project, the project group can be changed only to another Time and material group.</P>



<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type and criteria</p></th>
<th><p>Time and material</p></th>
<th><p>Fixed-price</p></th>
<th><p>Investment</p></th>
<th><p>Internal</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Subscription</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## See also

[Change the project group](change-the-project-group.md)

  


