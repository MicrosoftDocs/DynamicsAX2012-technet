---
title: 'Deprecated: Ledger budget form and table'
TOCTitle: Ledger budget form and table
ms:assetid: 60c60aa8-aa40-4590-bfe4-b4538142cffb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527129(v=AX.60)
ms:contentKeyID: 59623258
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Ledger budget form and table 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, Ledger budget is the name of the form and table where budget amounts for ledger accounts are captured.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>The budget functionality in Microsoft Dynamics AX 2012 was rewritten and extended to include additional functionality, such as budget control.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Ledger budget has been replaced by budget register entries. Budget register entries enable budget amounts to be entered by using a header/line concept. An organization can perform the following tasks:</p>
<ul>
<li><p>Determine which dimensions are available for budgeting.</p></li>
<li><p>Define budget codes that are related to budget types, for an additional audit trail of changes to a budget.</p></li>
<li><p>Allocate a budget across periods.</p></li>
<li><p>Allocate a budget across dimensions.</p></li>
<li><p>Replicate budget amounts.</p></li>
<li><p>Use a web service for integrations to budget register entries.</p></li>
<li><p>Use the budget transaction approval workflow.</p></li>
<li><p>Use the <strong>Budget versus actual</strong> inquiry and report.</p></li>
<li><p>Create budget register entries by using Project, Demand, Supply, and Fixed asset budgets.</p></li>
</ul>
<div class="alert">

> [!NOTE]
> <P>In AX 2009, a user could also transfer cost accounting budgets to Ledger budget. This is not supported in AX 2012, because the implementation of the new dimension framework in cost accounting does not enable data to flow outside of cost accounting.</P>


</div>
<p>For more information, see the product-wide feature topics <a href="basic-budgeting-and-budget-control.md">Basic budgeting and budget control</a> and <a href="what-s-new-ledger-and-subledger-lines-and-distributions.md">What's new: Ledger and subledger lines and distributions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Budgeting</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Preprocessing converts ledger budget records to budget register entries in AX 2012.</p></td>
</tr>
</tbody>
</table>

  


