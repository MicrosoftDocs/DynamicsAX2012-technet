---
title: OrderSearchType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderSearchType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.ordersearchtype(v=AX.60)
ms:contentKeyID: 65317829
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType.ConsolidateOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType.SalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType.SalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# OrderSearchType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The type of the search to be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration OrderSearchType
'Usage
Dim instance As OrderSearchType
```

``` csharp
public enum OrderSearchType
```

``` c++
public enum class OrderSearchType
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
<td>None</td>
<td>No type defined.</td>
</tr>
<tr class="even">
<td></td>
<td>SalesOrder</td>
<td>Search sales orders only. Sales transactions will be filtered out.</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesTransaction</td>
<td>Search sales transactions only. Sales orders will be filtered out.</td>
</tr>
<tr class="even">
<td></td>
<td>ConsolidateOrder</td>
<td>Search consolidated orders. All sales transactions related to the same orders will be coalesced into a single result with latest order status.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

