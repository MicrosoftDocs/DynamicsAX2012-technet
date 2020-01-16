---
title: DiscountBase.IsDiscountAllowedForCatalogIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: IsDiscountAllowedForCatalogIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountAllowedForCatalogIds(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.isdiscountallowedforcatalogids(v=AX.60)
ms:contentKeyID: 62213193
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountAllowedForCatalogIds
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountAllowedForCatalogIds Method

Determines if the discount is allowed for the specified catalog identifiers, based on the discount price groups for this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function IsDiscountAllowedForCatalogIds ( _
    priceContext As PriceContext, _
    discountPriceGroups As ISet(Of String), _
    itemCatalogIds As ISet(Of Long) _
) As Boolean
'Usage
Dim priceContext As PriceContext
Dim discountPriceGroups As ISet(Of String)
Dim itemCatalogIds As ISet(Of Long)
Dim returnValue As Boolean

returnValue = DiscountBase.IsDiscountAllowedForCatalogIds(priceContext, _
    discountPriceGroups, itemCatalogIds)
```

``` csharp
protected static bool IsDiscountAllowedForCatalogIds(
    PriceContext priceContext,
    ISet<string> discountPriceGroups,
    ISet<long> itemCatalogIds
)
```

``` c++
protected:
static bool IsDiscountAllowedForCatalogIds(
    PriceContext^ priceContext, 
    ISet<String^>^ discountPriceGroups, 
    ISet<long long>^ itemCatalogIds
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - discountPriceGroups  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - itemCatalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the discount is allowed for this catalog, false otherwise.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

