---
title: PriceContextHelper.GetAllPriceGroupIdsForDiscount Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetAllPriceGroupIdsForDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupIdsForDiscount(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getallpricegroupidsfordiscount(v=AX.60)
ms:contentKeyID: 62209589
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupIdsForDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetAllPriceGroupIdsForDiscount Method

Get all price group identifiers from price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAllPriceGroupIdsForDiscount ( _
    priceContext As PriceContext _
) As IEnumerable(Of Long)
'Usage
Dim priceContext As PriceContext
Dim returnValue As IEnumerable(Of Long)

returnValue = PriceContextHelper.GetAllPriceGroupIdsForDiscount(priceContext)
```

``` csharp
public static IEnumerable<long> GetAllPriceGroupIdsForDiscount(
    PriceContext priceContext
)
```

``` c++
public:
static IEnumerable<long long>^ GetAllPriceGroupIdsForDiscount(
    PriceContext^ priceContext
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
All price groups.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

