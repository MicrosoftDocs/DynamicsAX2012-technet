---
title: DiscountOfferMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountOfferMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountoffermethod(v=AX.60)
ms:contentKeyID: 49836738
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod.DiscountAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod.DiscountPercent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod.OfferPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod.OfferPriceIncludingTax
dev_langs:
- CSharp
- C++
- VB
---

# DiscountOfferMethod Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Specific method by which the discount is applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DiscountOfferMethod
'Usage
Dim instance As DiscountOfferMethod
```

``` csharp
public enum DiscountOfferMethod
```

``` c++
public enum class DiscountOfferMethod
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
<td>DiscountPercent</td>
<td>The discount is a percent-off.</td>
</tr>
<tr class="even">
<td></td>
<td>DiscountAmount</td>
<td>The discount is an amount-off.</td>
</tr>
<tr class="odd">
<td></td>
<td>OfferPrice</td>
<td>A fixed discount price.</td>
</tr>
<tr class="even">
<td></td>
<td>OfferPriceIncludingTax</td>
<td>A fixed discount price including tax.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailDiscountOfferLineDiscMethodBase enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

