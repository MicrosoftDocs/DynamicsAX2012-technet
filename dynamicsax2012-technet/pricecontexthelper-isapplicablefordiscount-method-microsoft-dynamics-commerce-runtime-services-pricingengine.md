---
title: PriceContextHelper.IsApplicableForDiscount Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: IsApplicableForDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.IsApplicableForDiscount(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.isapplicablefordiscount(v=AX.60)
ms:contentKeyID: 62213535
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.IsApplicableForDiscount
dev_langs:
- CSharp
- C++
- VB
---

# IsApplicableForDiscount Method

Check whether it is applicable for retail discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsApplicableForDiscount ( _
    priceContext As PriceContext, _
    discountPriceGroups As ISet(Of String), _
    itemCatalogIds As ISet(Of Long) _
) As Boolean
'Usage
Dim priceContext As PriceContext
Dim discountPriceGroups As ISet(Of String)
Dim itemCatalogIds As ISet(Of Long)
Dim returnValue As Boolean

returnValue = PriceContextHelper.IsApplicableForDiscount(priceContext, _
    discountPriceGroups, itemCatalogIds)
```

``` csharp
public static bool IsApplicableForDiscount(
    PriceContext priceContext,
    ISet<string> discountPriceGroups,
    ISet<long> itemCatalogIds
)
```

``` c++
public:
static bool IsApplicableForDiscount(
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
True if it is applicable.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

