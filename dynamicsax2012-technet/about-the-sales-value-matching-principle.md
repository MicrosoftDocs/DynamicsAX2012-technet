---
title: About the sales value matching principle
TOCTitle: About the sales value matching principle
ms:assetid: 6cfbc581-b35f-4550-b1b8-6e6fb819cfe4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571207(v=AX.60)
ms:contentKeyID: 36058017
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrued revenue
- reverse accrued revenue
- reverse estimate
- sales value
---

# About the sales value matching principle [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following is an overview of how and where the **Accrued revenue - sales value** account is applied and what parameter setup is required in the **Project groups** and **Line properties** forms.

## Account type

Profit and loss.

## Availability

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>License code</p></th>
<th><p>Configuration code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Project II</p></td>
<td><p>Work in process</p></td>
</tr>
</tbody>
</table>


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
<td><p>Hour</p>
<p>Item</p>
<p>Expense</p>
<p>Fee</p></td>
<td><p>Fixed-price</p>
<p>Time and material</p></td>
<td><p>Profit and loss</p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

  - For fixed-price projects, in the **Project groups** form, on the **Estimate** FastTab, select **Sales value** in the **Matching principle** field.

  - For time and material projects, in the **Line properties** form, on the **General** FastTab, select the **Accrue revenue** check box. For time and material projects, revenue must be accrued when fee, hour, item, and expense transactions are posted.

## See also

[Select accrued revenue for posting](select-accrued-revenue-for-posting.md)

[Project groups (form)](https://technet.microsoft.com/en-us/library/aa590435\(v=ax.60\))

[Line properties (form)](https://technet.microsoft.com/en-us/library/aa590082\(v=ax.60\))

[Estimate (form)](https://technet.microsoft.com/en-us/library/aa590971\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

