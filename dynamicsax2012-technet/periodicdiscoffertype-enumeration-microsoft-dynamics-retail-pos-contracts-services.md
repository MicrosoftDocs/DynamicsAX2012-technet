---
title: PeriodicDiscOfferType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PeriodicDiscOfferType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.periodicdiscoffertype(v=AX.60)
ms:contentKeyID: 47344317
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType.MixMatch
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType.MultiBuy
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType.Offer
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType.Promotion
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType.Threshold
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscOfferType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.PeriodicDiscOfferType interface defines the type of the discount: offer, promotion, quantity discount, or mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PeriodicDiscOfferType
'Usage
Dim instance As PeriodicDiscOfferType
```

``` csharp
public enum PeriodicDiscOfferType
```

``` c++
public enum class PeriodicDiscOfferType
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
<td>MultiBuy</td>
<td>Indicates the discount is a quantity discount.</td>
</tr>
<tr class="even">
<td></td>
<td>MixMatch</td>
<td>Indicates the discount is a mix and match discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>Offer</td>
<td>Indicates the discount is a standard discount offer.</td>
</tr>
<tr class="even">
<td></td>
<td>Promotion</td>
<td>Indicates the discount is an offer which is applied as part of the base item price.</td>
</tr>
<tr class="odd">
<td></td>
<td>Threshold</td>
<td></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

