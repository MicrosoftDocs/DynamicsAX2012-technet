---
title: PriceDiscType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PriceDiscType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.pricedisctype(v=AX.60)
ms:contentKeyID: 47344316
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.PricePurch
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.PriceSales
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.EndDiscPurch
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.MultiLineDiscSales
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.LineDiscSales
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.MultiLineDiscPurch
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.LineDiscPurch
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType.EndDiscSales
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.PriceDiscType interface specifies the type of a discount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PriceDiscType
'Usage
Dim instance As PriceDiscType
```

``` csharp
public enum PriceDiscType
```

``` c++
public enum class PriceDiscType
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
<td>PricePurch</td>
<td>This method is not currently used.</td>
</tr>
<tr class="even">
<td></td>
<td>LineDiscPurch</td>
<td>This method is not currently used.</td>
</tr>
<tr class="odd">
<td></td>
<td>MultiLineDiscPurch</td>
<td>This method is not currently used.</td>
</tr>
<tr class="even">
<td></td>
<td>EndDiscPurch</td>
<td>This method is not currently used.</td>
</tr>
<tr class="odd">
<td></td>
<td>PriceSales</td>
<td>This method is not currently used.</td>
</tr>
<tr class="even">
<td></td>
<td>LineDiscSales</td>
<td>Predefined line discount for an item.</td>
</tr>
<tr class="odd">
<td></td>
<td>MultiLineDiscSales</td>
<td>Predefined discount for the multiple of a certain item.</td>
</tr>
<tr class="even">
<td></td>
<td>EndDiscSales</td>
<td>Total discount value granted at the end of a transaction retroactive to each item.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

