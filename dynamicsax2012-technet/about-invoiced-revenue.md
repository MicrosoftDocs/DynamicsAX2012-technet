---
title: About invoiced revenue
TOCTitle: About invoiced revenue
ms:assetid: 13122f4c-7824-488f-997b-71319907fb75
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496594(v=AX.60)
ms:contentKeyID: 36966696
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- profit and loss
- invoiced revenue
---

# About invoiced revenue [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of how and where invoiced revenue accounts are applied, and what parameter setup is required to post to these accounts. General invoiced revenue accounts apply only to Time and material projects. On-account invoiced revenue accounts apply only to Time and material and Fixed-price projects.

## How the account is applied

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Project type</p></th>
<th><p>Statement type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Hours</p>
<p>Expense</p>
<p>Fee</p>
<p>Item</p></td>
<td><p>Time and material</p></td>
<td><p>Profit and loss</p></td>
</tr>
<tr class="even">
<td><p>On-account</p></td>
<td><p>Time and material</p>
<p>Fixed-price</p></td>
<td><p>Profit and loss</p>
<p>On-account</p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

**Invoiced revenue**

  - In the **Line properties** form, on the **General** FastTab, the **Chargeable** check box must be selected under **Invoicing**.

**Invoiced revenue – On-account**

  - In the **Project groups** form, on the **Ledger** FastTab, **Profit and loss** must be selected in the **On-account invoicing** field.
    
    When a new project group is created, the **On-account invoicing** field is set to a default value that is based on the project type. This default value can be changed only for Time and material projects and Fixed-price projects. For other project types, the default value cannot be changed.
    
    For Time and material projects, the default value is **Balance**. For Fixed-price projects, the default value is **Profit and loss**.
    

    > [!NOTE]
    > <P>For Fixed-price projects, selections made in the <STRONG>Fixed-price</STRONG> area in the <STRONG>Estimate</STRONG> form can change the values that are permitted in this field.</P>



## Actions and account crediting

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Result</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoicing</p></td>
<td><p>The account is credited when Time and material projects are invoiced.</p></td>
</tr>
<tr class="even">
<td><p>On-account invoicing</p></td>
<td><p>The account is credited when it is invoiced.</p></td>
</tr>
</tbody>
</table>


## See also

[Credit invoiced amounts in projects](credit-invoiced-amounts-in-projects.md)

[About on-account accrued revenue](about-on-account-accrued-revenue.md)

[Recognize revenue](recognize-revenue.md)

[About accrued revenue](about-accrued-revenue.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

