---
title: About funds (Public sector)
TOCTitle: About funds (Public sector)
ms:assetid: e05aadc3-9f25-4620-88a0-d63bdde8058e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208594(v=AX.60)
ms:contentKeyID: 36056381
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fund type
- GAAP
- GASB
- fund
- fund class
audience: Application User
ms.search.region: Denmark, France
---

# About funds (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A fund is a self-balancing set of financial books that is used to control and monitor the planned use of resources, often in compliance with legal and administrative requirements. Organizations use funds to demonstrate their fiscal accountability.

In Microsoft Dynamics AX, your organization can set up a system of funds that are grouped by the fund types that you create. Funds can be grouped also among three fund classes: Governmental, Proprietary, and Fiduciary. Many funds can be included in a single high-level report, but each fund remains a separate fiscal and accounting entity with its own general ledger, income statements, and balance sheet reports.

Each fund must have a unique fund number. In Microsoft Dynamics AX, fund numbers are used as dimension values in financial account numbers where a dimension has been mapped to a fund. When an account number is linked to a particular fund, it belongs to the set of financial books that are contained by that fund.


> [!NOTE]
> <P>The Governmental Accounting Standards Board (GASB) recommends a set of Generally Accepted Accounting Principles (GAAP) for state and local governmental accounting. You can use these standards when you set up your own system of funds and fund types.</P>



## Fund number and name

The following table shows examples of funds:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fund number</p></th>
<th><p>Fund name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1103</p></td>
<td><p>General Fund (Federal)</p></td>
</tr>
<tr class="even">
<td><p>1105</p></td>
<td><p>General Fund (Enterprise)</p></td>
</tr>
<tr class="odd">
<td><p>1343</p></td>
<td><p>School of Technology</p></td>
</tr>
<tr class="even">
<td><p>1372</p></td>
<td><p>Information Technology</p></td>
</tr>
<tr class="odd">
<td><p>2501</p></td>
<td><p>Farmers Market</p></td>
</tr>
<tr class="even">
<td><p>2541</p></td>
<td><p>Utilities Commission</p></td>
</tr>
<tr class="odd">
<td><p>2723</p></td>
<td><p>Courier Service</p></td>
</tr>
<tr class="even">
<td><p>2738</p></td>
<td><p>Worker’s Compensation Fund</p></td>
</tr>
<tr class="odd">
<td><p>3320</p></td>
<td><p>Comprehensive Major Medical Plan</p></td>
</tr>
<tr class="even">
<td><p>3324</p></td>
<td><p>Deferred Compensation</p></td>
</tr>
<tr class="odd">
<td><p>3912</p></td>
<td><p>Local Sales Tax Collections</p></td>
</tr>
<tr class="even">
<td><p>3914</p></td>
<td><p>Clerk of Courts</p></td>
</tr>
</tbody>
</table>


## Grouped by fund type

The following table shows funds that are grouped by fund type:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fund type</p></th>
<th><p>Fund number</p></th>
<th><p>Fund name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>General Fund</p></td>
<td><p>1103</p></td>
<td><p>General Fund (Federal)</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>1105</p></td>
<td><p>General Fund (Enterprise)</p></td>
</tr>
<tr class="odd">
<td><p>Special Revenue Funds</p></td>
<td><p>1343</p></td>
<td><p>School of Technology</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>1372</p></td>
<td><p>Information Technology</p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Funds</p></td>
<td><p>2501</p></td>
<td><p>Farmers Market</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>2541</p></td>
<td><p>Utilities Commission</p></td>
</tr>
<tr class="odd">
<td><p>Internal Service Funds</p></td>
<td><p>2723</p></td>
<td><p>Courier Service</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>2738</p></td>
<td><p>Worker’s Compensation Fund</p></td>
</tr>
<tr class="odd">
<td><p>Pension Trust Funds</p></td>
<td><p>3320</p></td>
<td><p>Comprehensive Major Medical Plan</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>3324</p></td>
<td><p>Deferred Compensation</p></td>
</tr>
<tr class="odd">
<td><p>Agency Funds</p></td>
<td><p>3912</p></td>
<td><p>Local Sales Tax Collections</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>3914</p></td>
<td><p>Clerk of Courts</p></td>
</tr>
</tbody>
</table>


## Grouped by fund class

The following table shows funds that are grouped by fund class:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fund class</p></th>
<th><p>Fund type</p></th>
<th><p>Fund number</p></th>
<th><p>Fund name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Governmental</p></td>
<td><p>General Fund</p></td>
<td><p>1103</p></td>
<td><p>General Fund (Federal)</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>1105</p></td>
<td><p>General Fund (Enterprise)</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Special Revenue Funds</p></td>
<td><p>1343</p></td>
<td><p>School of Technology</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>1372</p></td>
<td><p>Information Technology</p></td>
</tr>
<tr class="odd">
<td><p>Proprietary</p></td>
<td><p>Enterprise Funds</p></td>
<td><p>2501</p></td>
<td><p>Farmers Market</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>2541</p></td>
<td><p>Utilities Commission</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Internal Service Funds</p></td>
<td><p>2723</p></td>
<td><p>Courier Service</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>2738</p></td>
<td><p>Worker’s Compensation Fund</p></td>
</tr>
<tr class="odd">
<td><p>Fiduciary</p></td>
<td><p>Pension Trust Funds</p></td>
<td><p>3320</p></td>
<td><p>Comprehensive Major Medical Plan</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>3324</p></td>
<td><p>Deferred Compensation</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Agency Funds</p></td>
<td><p>3912</p></td>
<td><p>Local Sales Tax Collections</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>3914</p></td>
<td><p>Clerk of Courts</p></td>
</tr>
</tbody>
</table>


## See also

[Funds (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208514\(v=ax.60\))

[Fund types (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208583\(v=ax.60\))

  


