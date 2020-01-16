---
title: DiscountMethodType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DiscountMethodType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.discountmethodtype(v=AX.60)
ms:contentKeyID: 47344325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.MultiplyDiscountPercent
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.MultiplyDealPrice
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.DealPrice
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.DiscountAmount
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.LineSpecific
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.LeastExpensive
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType.DiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethodType Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.DiscountMethodType interface indicates the method that is used to calculate the discount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DiscountMethodType
'Usage
Dim instance As DiscountMethodType
```

``` csharp
public enum DiscountMethodType
```

``` c++
public enum class DiscountMethodType
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
<td>DealPrice</td>
<td>Indicates that discount value is a price for the discounted item.</td>
</tr>
<tr class="even">
<td></td>
<td>DiscountPercent</td>
<td>Indicates that discount value is a percent off the item's price.</td>
</tr>
<tr class="odd">
<td></td>
<td>DiscountAmount</td>
<td>Indicates that discount value is an amount off the item's price.</td>
</tr>
<tr class="even">
<td></td>
<td>LeastExpensive</td>
<td>Indicates that discount value is the price of the least expensive item on the discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>LineSpecific</td>
<td>Indicates the discount method is deferred to the discount line defined for each item.</td>
</tr>
<tr class="even">
<td></td>
<td>MultiplyDealPrice</td>
<td>Indicates the discount value is a price for the discounted item on quantity discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>MultiplyDiscountPercent</td>
<td>Indicates the discount value is a percent off the item's price on quantity discount.</td>
</tr>
</tbody>
</table>


## Remarks

With the exception of least expensive or line-specific, these will define how a numeric discount value is to be interpreted.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

