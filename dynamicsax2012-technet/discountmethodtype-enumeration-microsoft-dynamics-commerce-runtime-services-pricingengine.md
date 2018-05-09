---
title: DiscountMethodType Enumeration (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: DiscountMethodType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountmethodtype(v=AX.60)
ms:contentKeyID: 62213728
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.DiscountPercent
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.MultiplyDiscountPercent
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.DiscountAmount
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.LineSpecific
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.LeastExpensive
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.MultiplyDealPrice
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType.DealPrice
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethodType Enumeration

This indicates the method used to calculate the discount. Except for Least Expensive or Line-specific, these will define how a numeric discount value (defined elsewhere) is to be interpreted. E.g. if this is DiscountPercent, the value represents a percent off, if this is DealPrice, the value represents the price of the discounted item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

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
<td>Discount value is a price for the discounted item.</td>
</tr>
<tr class="even">
<td></td>
<td>DiscountPercent</td>
<td>Discount value is a percent off the item's price.</td>
</tr>
<tr class="odd">
<td></td>
<td>DiscountAmount</td>
<td>Discount value is an amount off the item's price.</td>
</tr>
<tr class="even">
<td></td>
<td>LeastExpensive</td>
<td>Discount amount off should be the price of the least expensive item on the discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>LineSpecific</td>
<td>The discount method is deferred to the discount line defined for each item.</td>
</tr>
<tr class="even">
<td></td>
<td>MultiplyDealPrice</td>
<td>Discount value is a price for the discounted item on quantity discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>MultiplyDiscountPercent</td>
<td>Discount value is a percent off the item's price on quantity discount.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

