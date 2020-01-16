---
title: DiscountMethod Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DiscountMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.discountmethod(v=AX.60)
ms:contentKeyID: 47343868
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod.DiscountAmount
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod.DiscountPercent
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod.OfferPrice
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod.OfferPriceInclTax
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethod Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethod interface specifies the specific method by which the discount is applied.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DiscountMethod
'Usage
Dim instance As DiscountMethod
```

``` csharp
public enum DiscountMethod
```

``` c++
public enum class DiscountMethod
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
<td>0 (Discount is a percent-off)</td>
</tr>
<tr class="even">
<td></td>
<td>DiscountAmount</td>
<td>1 (Discount is an amount-off)</td>
</tr>
<tr class="odd">
<td></td>
<td>OfferPrice</td>
<td>2 (fixed discount price)</td>
</tr>
<tr class="even">
<td></td>
<td>OfferPriceInclTax</td>
<td>3 (fixed discount price including tax)</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

