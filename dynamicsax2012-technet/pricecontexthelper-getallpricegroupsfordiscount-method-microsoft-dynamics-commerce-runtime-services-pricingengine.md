---
title: PriceContextHelper.GetAllPriceGroupsForDiscount Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetAllPriceGroupsForDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupsForDiscount(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getallpricegroupsfordiscount(v=AX.60)
ms:contentKeyID: 62204961
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupsForDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetAllPriceGroupsForDiscount Method

Get all price groups from price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAllPriceGroupsForDiscount ( _
    priceContext As PriceContext _
) As HashSet(Of String)
'Usage
Dim priceContext As PriceContext
Dim returnValue As HashSet(Of String)

returnValue = PriceContextHelper.GetAllPriceGroupsForDiscount(priceContext)
```

``` csharp
public static HashSet<string> GetAllPriceGroupsForDiscount(
    PriceContext priceContext
)
```

``` c++
public:
static HashSet<String^>^ GetAllPriceGroupsForDiscount(
    PriceContext^ priceContext
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Collections.Generic.HashSet](https://technet.microsoft.com/library/bb359438\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
All price groups.  

## Remarks

We could have made it an C\# extension. Leave it here for all price context logic.

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

