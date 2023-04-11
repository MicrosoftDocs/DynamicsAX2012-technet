---
title: ConcurrencyMode Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ConcurrencyMode Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.concurrencymode(v=AX.60)
ms:contentKeyID: 47344401
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode.BestPrice
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode.Compounded
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode.Exclusive
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode interface specifies how discount should interact with other discounts on a line.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ConcurrencyMode
'Usage
Dim instance As ConcurrencyMode
```

``` csharp
public enum ConcurrencyMode
```

``` c++
public enum class ConcurrencyMode
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
<td>Exclusive</td>
<td>Overrides all other discounts If this discount applies.</td>
</tr>
<tr class="even">
<td></td>
<td>BestPrice</td>
<td>Applies the best price between all discounts, If this discount applies.</td>
</tr>
<tr class="odd">
<td></td>
<td>Compounded</td>
<td>Compounds all discounts and marks them as compounded, If this discount applies.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

