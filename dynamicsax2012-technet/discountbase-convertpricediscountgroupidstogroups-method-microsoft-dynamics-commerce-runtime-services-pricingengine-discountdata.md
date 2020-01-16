---
title: DiscountBase.ConvertPriceDiscountGroupIdsToGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ConvertPriceDiscountGroupIdsToGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ConvertPriceDiscountGroupIdsToGroups(System.Collections.Generic.ISet{System.Int64},Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.convertpricediscountgroupidstogroups(v=AX.60)
ms:contentKeyID: 62212379
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ConvertPriceDiscountGroupIdsToGroups
dev_langs:
- CSharp
- C++
- VB
---

# ConvertPriceDiscountGroupIdsToGroups Method

Translates price discount groups from record identifiers into the text identifiers for the groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function ConvertPriceDiscountGroupIdsToGroups ( _
    priceDiscountGroupIds As ISet(Of Long), _
    priceContext As PriceContext _
) As IEnumerable(Of String)
'Usage
Dim priceDiscountGroupIds As ISet(Of Long)
Dim priceContext As PriceContext
Dim returnValue As IEnumerable(Of String)

returnValue = DiscountBase.ConvertPriceDiscountGroupIdsToGroups(priceDiscountGroupIds, _
    priceContext)
```

``` csharp
protected static IEnumerable<string> ConvertPriceDiscountGroupIdsToGroups(
    ISet<long> priceDiscountGroupIds,
    PriceContext priceContext
)
```

``` c++
protected:
static IEnumerable<String^>^ ConvertPriceDiscountGroupIdsToGroups(
    ISet<long long>^ priceDiscountGroupIds, 
    PriceContext^ priceContext
)
```

#### Parameters

  - priceDiscountGroupIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
A collection of text identifiers for the price discount groups.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

