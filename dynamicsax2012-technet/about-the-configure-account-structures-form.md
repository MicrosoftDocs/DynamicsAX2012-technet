---
title: About the Configure account structures form
TOCTitle: About the Configure account structures form
ms:assetid: 621b68f2-20af-404d-8932-402959b0cb11
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209188(v=AX.60)
ms:contentKeyID: 36057664
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- chart of accounts
- account structure
- account structures
- configure account structures
---

# About the Configure account structures form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A relational chart of accounts uses an account structure that requires that you set up valid accounts and financial dimension values, and then set up rules to specify how the accounts and dimensions will come together to create account structures. Setting up valid combinations helps make sure that data entry is accurate.

You can use the **Configure account structures** form to create one or more account structures. Account structures consist of main accounts and can include financial dimension segments. The account structures are used to define the valid combinations which, together with the main accounts, form a chart of accounts.

You can view the whole account structure, which includes the valid combination of values that can be entered in a dimension, in the following ways:

  - Horizontally – View the columns that show the dimensions that make up the structure.

  - Vertically – View the hierarchical visualization of the rules that describe how the combinations behave.

When you use multiple account structures, you can track information for specific accounts without affecting information in other accounts.

## The Configure account structures form

 ![Configure account structures form](images/Hh209188.ConfigureAccountStructuresForm(AX.60).jpg "Configure account structures form")

## Account structure elements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Number</p></th>
<th><p>Element</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Active account structure</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Draft account structure</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Account structure segment</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Filter button</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p><strong>Add segment</strong> button</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p><strong>Action menu</strong></p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p><strong>Add %1 node</strong> button</p></td>
</tr>
</tbody>
</table>


## Account structure terms and definitions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Term</p></th>
<th><p>Definition</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Account structure</strong></p></td>
<td><p>A structure that defines the valid combinations of main account and dimension values.</p></td>
</tr>
<tr class="even">
<td><p><strong>Segment</strong></p></td>
<td><p>Each column in the <strong>Configure account structures</strong> form. Segments consist of main accounts or financial dimensions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Filter button</strong></p></td>
<td><p>A button that opens the <strong>Which values are allowed for the %1 field</strong> form, where you can specify the values that are allowed for each segment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Action menu</strong></p></td>
<td><p>A menu icon that is displayed next to segment rows. Click the <strong>Action menu</strong> to set active dates and to copy, paste, delete, or move segments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Combination</strong></p></td>
<td><p>The arrangement of account segments, advanced rules, and criteria.</p></td>
</tr>
<tr class="even">
<td><p><strong>Advanced rule</strong></p></td>
<td><p>A relationship principle that helps make sure that dimension values are entered correctly, and are filtered and validated according to the dimension structure. Advanced rules are defined for each account structure.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Financial dimension</strong></p></td>
<td><p>An attribute that additionally defines an entity.</p></td>
</tr>
<tr class="even">
<td><p><strong>Ledger account</strong></p></td>
<td><p>The combination of main account and other dimension values, as defined by the chart of accounts, and which classifies financial activity.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main account</strong></p></td>
<td><p>The type of record—asset, liability, revenue, expense, or owner’s equity—that is used for recording individual transactions in an accounting system.</p></td>
</tr>
</tbody>
</table>


## See also

[Configure account structures (form)](https://technet.microsoft.com/en-us/library/hh227362\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

