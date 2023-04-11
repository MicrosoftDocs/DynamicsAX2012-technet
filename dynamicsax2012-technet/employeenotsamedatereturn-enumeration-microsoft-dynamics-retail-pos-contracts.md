---
title: EmployeeNotSameDateReturn Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: EmployeeNotSameDateReturn Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.EmployeeNotSameDateReturn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.employeenotsamedatereturn(v=AX.60)
ms:contentKeyID: 62202775
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeeNotSameDateReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeeNotSameDateReturn.Reject
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeeNotSameDateReturn.Warn
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeeNotSameDateReturn.Accept
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeNotSameDateReturn Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Employee-based permissions for Not same date return operation AX enum RetailNotSameDateReturn\_RU

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration EmployeeNotSameDateReturn
'Usage
Dim instance As EmployeeNotSameDateReturn
```

``` csharp
public enum EmployeeNotSameDateReturn
```

``` c++
public enum class EmployeeNotSameDateReturn
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>Reject</td>
<td>The employee cannot return goods at not same date as sale.</td>
</tr>
<tr class="even">
<td></td>
<td>Warn</td>
<td>The employee get a warning dialog then can proceed or decline return goods at not same date as sale.</td>
</tr>
<tr class="odd">
<td></td>
<td>Accept</td>
<td>The employee can return goods at not same date as sale.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

