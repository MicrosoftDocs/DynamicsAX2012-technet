---
title: PriceContextHelper.GetAllPriceGroupsForPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetAllPriceGroupsForPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupsForPrice(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getallpricegroupsforprice(v=AX.60)
ms:contentKeyID: 62208179
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAllPriceGroupsForPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetAllPriceGroupsForPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all price groups for price from price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAllPriceGroupsForPrice ( _
    priceContext As PriceContext _
) As ISet(Of String)
'Usage
Dim priceContext As PriceContext
Dim returnValue As ISet(Of String)

returnValue = PriceContextHelper.GetAllPriceGroupsForPrice(priceContext)
```

``` csharp
public static ISet<string> GetAllPriceGroupsForPrice(
    PriceContext priceContext
)
```

``` c++
public:
static ISet<String^>^ GetAllPriceGroupsForPrice(
    PriceContext^ priceContext
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
All price groups for price.  

## Remarks

We could have made it an C\# extension. Leave it here for all price context logic.

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

