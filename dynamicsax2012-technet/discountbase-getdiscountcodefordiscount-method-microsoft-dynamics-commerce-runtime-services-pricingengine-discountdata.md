---
title: DiscountBase.GetDiscountCodeForDiscount Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetDiscountCodeForDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetDiscountCodeForDiscount(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.getdiscountcodefordiscount(v=AX.60)
ms:contentKeyID: 62214009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetDiscountCodeForDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodeForDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the (first) discount code from the transaction that triggered the discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function GetDiscountCodeForDiscount ( _
    transaction As SalesTransaction _
) As String
'Usage
Dim transaction As SalesTransaction
Dim returnValue As String

returnValue = Me.GetDiscountCodeForDiscount(transaction)
```

``` csharp
protected string GetDiscountCodeForDiscount(
    SalesTransaction transaction
)
```

``` c++
protected:
String^ GetDiscountCodeForDiscount(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The first matching discount code from the transaction that is contained in the collection of required discount codes for this discount.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

