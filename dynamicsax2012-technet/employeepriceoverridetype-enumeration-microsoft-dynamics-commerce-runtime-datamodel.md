---
title: EmployeePriceOverrideType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeePriceOverrideType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepriceoverridetype(v=AX.60)
ms:contentKeyID: 62208408
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType.HigherAndLower
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType.NotAllowed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType.LowerOnly
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePriceOverrideType.HigherOnly
dev_langs:
- CSharp
- C++
- VB
---

# EmployeePriceOverrideType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the type of employee price override.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration EmployeePriceOverrideType
'Usage
Dim instance As EmployeePriceOverrideType
```

``` csharp
[DataContractAttribute]
public enum EmployeePriceOverrideType
```

``` c++
[DataContractAttribute]
public enum class EmployeePriceOverrideType
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

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

