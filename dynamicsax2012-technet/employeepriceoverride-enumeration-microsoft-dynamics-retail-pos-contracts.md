---
title: EmployeePriceOverride Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: EmployeePriceOverride Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.employeepriceoverride(v=AX.60)
ms:contentKeyID: 47128626
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride.NotAllowed
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride.LowerOnly
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride.HigherOnly
- Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride.HigherAndLower
dev_langs:
- CSharp
- C++
- VB
---

# EmployeePriceOverride Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Specifies the worker-based permissions for the PriceOverride operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration EmployeePriceOverride
'Usage
Dim instance As EmployeePriceOverride
```

``` csharp
public enum EmployeePriceOverride
```

``` c++
public enum class EmployeePriceOverride
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
<td>HigherAndLower</td>
<td>The employee can override prices, and set a higher or lower price.</td>
</tr>
<tr class="even">
<td></td>
<td>HigherOnly</td>
<td>The employee can override prices but can set only a higher price.</td>
</tr>
<tr class="odd">
<td></td>
<td>LowerOnly</td>
<td>The employee can override prices but can set only a lower price.</td>
</tr>
<tr class="even">
<td></td>
<td>NotAllowed</td>
<td>The employee cannot override prices.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

