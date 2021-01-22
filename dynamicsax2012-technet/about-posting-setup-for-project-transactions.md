---
title: About posting setup for project transactions
TOCTitle: About posting setup for project transactions
ms:assetid: 7820b0f9-9d28-4cb5-8ec4-aef7edc0956b
ms:mtpsurl: https://technet.microsoft.com/library/Aa550048(v=AX.60)
ms:contentKeyID: 36058219
author: Khairunj
ms.author: daxcpft
ms.date: 10/15/2014
mtps_version: v=AX.60
f1_keywords:
- project group
- posting setup
- project category
- set up posting
audience: Application User
ms.search.region: Global
---

# About posting setup for project transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use posting setup to specify the accounts to which project transactions should be posted.

You can post transactions according to projects, project groups, and funding sources, or according to categories and category groups, or any combination of these criteria. When you create project groups, you define the search priority as Project-first or Category-first to determine which posting rules take precedence when the system searches for posting accounts.

## Set up ledger posting in cost price accounts

You can set up ledger posting in cost price accounts either by transaction type or by project type.

## Transaction type

The following table shows which cost price accounts are applied by the input from the transaction types that are available in **Project management and accounting**.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Posting type</p></th>
<th><p>Hour</p></th>
<th><p>Expenses</p></th>
<th><p>Item</p></th>
<th><p>Fee</p></th>
<th><p>On account</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cost</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Payroll allocation</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP cost value accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Item cost</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP Cost value item accounts</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accrued loss</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP accrued loss accounts</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Intercompany cost</p>
<div class="alert">

> [!NOTE]
> <P>Projects for which timesheets are entered cannot have a ledger setting of <STRONG>No ledger</STRONG> or <STRONG>Never ledger</STRONG>.</P>


</div></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Project type

The following table shows what accounts are applied by the input from the project types available in **Project management and accounting**.

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
<th><p>Posting type</p></th>
<th><p>Fixed price</p></th>
<th><p>Time and material</p></th>
<th><p>Internal</p></th>
<th><p>Investment</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cost</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Payroll allocation</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP cost value accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Item cost</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP cost value item accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accrued loss</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>WIP accrued loss accounts</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Intercompany cost</p>
<div class="alert">

> [!NOTE]
> <P>Projects for which timesheets are entered cannot have a ledger setting of <STRONG>No ledger</STRONG> or <STRONG>Never ledger</STRONG>.</P>


</div></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


## Set up ledger posting in Sales price accounts

Set up ledger posting in sales price accounts by transaction type or by project type.

## Transaction type

The following table shows which sales price accounts are applied by the input from the transaction types available in **Project management and accounting**.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Posting type</p></th>
<th><p>Hour</p></th>
<th><p>Expenses</p></th>
<th><p>Item</p></th>
<th><p>Fee</p></th>
<th><p>On account</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoiced revenue</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>On-account invoiced revenue</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>Sales value and accrued value</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP sales value accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Accrued revenue through production</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP production accounts</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Accrued revenue through profit</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP profit accounts</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>On-account accrued revenue</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>WIP invoice on-account accounts</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>Subscription and accrued revenue</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP subscription accounts</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Intercompany revenue</p>
<div class="alert">

> [!NOTE]
> <P>Projects for which timesheets are entered cannot have a ledger setting of <STRONG>No ledger</STRONG> or <STRONG>Never ledger</STRONG>.</P>


</div></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Project type

The following table shows which sales price accounts are applied by the input from the project types available in the **Project management and accounting** module.

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
<th><p>Posting type</p></th>
<th><p>Fixed price</p></th>
<th><p>Time and material</p></th>
<th><p>Internal</p></th>
<th><p>Investment</p></th>
<th><p>Cost</p></th>
<th><p>Time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>About invoiced revenue</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>On-account invoiced revenue</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Sales value and accrued revenue</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP sales value accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Accrued revenue through production</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP production accounts</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Accrued revenue through profit</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP profit accounts</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>On-account accrued revenue</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP invoice on-account accounts</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Subscription and accrued revenue</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>WIP subscription accounts</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Intercompany revenue</p>
<div class="alert">

> [!NOTE]
> <P>Projects for which timesheets are entered cannot have a ledger setting of <STRONG>No ledger</STRONG> or <STRONG>Never ledger</STRONG>.</P>


</div></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


## Overview of transactions posted to specific ledger accounts

Transactions are posted to specific ledger accounts as follows:

  - Project and category are specified on the transaction.

  - The project specifies whether project transactions defer to project or category when searching ledger posting rules for an account. This setting is inherited from the project group.

  - When a transaction is posted, Microsoft Dynamics AX searches through the configurations in the **Ledger posting setup** form. The system searches first for a posting combination that matches the specific project and category. If it does not find this combination, the search continues using the priorities listed earlier in this topic. The search continues until the least specific combination (Project - All/Category - All), is found. If no combination is found, an error will be reported when you try to post a transaction.

## Cost price accounts

The available cost price accounts can be applied for the following combinations of project types and transaction types.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Cost price account</strong></p></th>
<th><p><strong>Project types</strong></p></th>
<th><p><strong>Transaction types</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Cost</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Time and material, Fixed-price, Investment, Cost, Internal, and Time</p></td>
<td><p>Hour, expense, and item, transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - cost value</strong> <br />
(Balance)</p></td>
<td><p>Time and material, Fixed-price, Investment project, and Internal</p></td>
<td><p>Hour and expense transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost - item</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Time and material, Fixed-price, Investment, and Internal</p></td>
<td><p>Item transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - cost value - item</strong></p></td>
<td><p>Time and material, Fixed-price, Investment, and Internal</p></td>
<td><p>Item transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payroll allocation</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Time and material, Fixed-price, Investment, Cost, Internal, and Time</p></td>
<td><p>Hour transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>Intercompany cost</strong></p>
<p></p></td>
<td><p>Time and material, Fixed-price, Investment, Cost, Internal, and Time</p></td>
<td><p>Hour transactions</p></td>
</tr>
</tbody>
</table>


## Sales price accounts

The available sales price accounts can be applied for the following combinations of project types and transaction types.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sales price account</p></th>
<th><p>Project types</p></th>
<th><p>Transaction types</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Invoiced revenue</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Time and material projects</p></td>
<td><p>Hour, expense, item, fee, and on-account transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoiced revenue - on-account</strong> <br />
(Profit &amp; loss/Balance)</p></td>
<td><p>Time and material and Fixed-price projects</p></td>
<td><p>On-account transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accrued revenue - sales value</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Time and material and Fixed-price projects</p></td>
<td><p>Hour, expense, item, and fee transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - sales value</strong> <br />
(Balance)</p></td>
<td><p>Time and material and Fixed-price projects</p></td>
<td><p>Hour, expense, item, and fee transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accrued revenue - production</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Fixed-price projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - production</strong> <br />
(Balance)</p></td>
<td><p>Fixed-price projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accrued revenue - profit</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Fixed-price projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - profit</strong> <br />
(Balance)</p></td>
<td><p>Fixed-price projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accrued revenue - on-account</strong> <br />
(Profit &amp; loss)</p></td>
<td><p>Fixed-price projects</p></td>
<td><p>On-account transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - Invoiced - on-account</strong> <br />
(Balance)</p></td>
<td><p>Time and material and Fixed-price projects</p></td>
<td><p>On-account transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accrued revenue - subscription</strong></p></td>
<td><p>Time and material projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - subscription</strong></p></td>
<td><p>Time and material projects</p></td>
<td><p>Fee transactions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Intercompany revenue</strong></p></td>
<td><p>Time and material, Fixed-price, Investment, Cost, Internal, and Time</p></td>
<td><p>Hour transactions</p></td>
</tr>
</tbody>
</table>


## Posting setup by project group or by category

The following table outlines posting setup by project group or by category and indicates the priority for ledger accounts on an individual project.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Priority</p></th>
<th><p>Account priority</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><ul>
<li><p>Project – Project, category</p></li>
<li><p>Category – Project, category</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><ul>
<li><p>Project – Project, category group</p></li>
<li><p>Category – Project group, category</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><ul>
<li><p>Project – Project, all categories</p></li>
<li><p>Category – All Projects, category</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><ul>
<li><p>Project – Project group, category</p></li>
<li><p>Category – Project, category group</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><ul>
<li><p>Project – Project group, category group</p></li>
<li><p>Category – Project group, category group</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><ul>
<li><p>Project – Project group, all categories</p></li>
<li><p>Category – All projects, category group</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><ul>
<li><p>Project – All projects, category</p></li>
<li><p>Category – Project, all categories</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><ul>
<li><p>Project – All projects, category group</p></li>
<li><p>Category – Project group, all categories</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>9</p></td>
<td><ul>
<li><p>Project – All projects, all categories</p></li>
<li><p>Category group – All projects, all categories</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Select accrued revenue for posting](select-accrued-revenue-for-posting.md)

[Configuring posting accounts](configuring-posting-accounts.md)

[Configuring ledger posting for projects](configuring-ledger-posting-for-projects.md)

[Ledger posting setup (form)](https://technet.microsoft.com/library/aa599270\(v=ax.60\))

[Posting (form)](https://technet.microsoft.com/library/aa551718\(v=ax.60\))

  


