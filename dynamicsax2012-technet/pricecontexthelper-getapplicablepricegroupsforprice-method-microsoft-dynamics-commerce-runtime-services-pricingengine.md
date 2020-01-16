---
title: PriceContextHelper.GetApplicablePriceGroupsForPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetApplicablePriceGroupsForPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetApplicablePriceGroupsForPrice(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getapplicablepricegroupsforprice(v=AX.60)
ms:contentKeyID: 62214618
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetApplicablePriceGroupsForPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetApplicablePriceGroupsForPrice Method

Get all applicable price price groups from price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetApplicablePriceGroupsForPrice ( _
    priceContext As PriceContext, _
    itemCatalogIds As ISet(Of Long) _
) As ISet(Of String)
'Usage
Dim priceContext As PriceContext
Dim itemCatalogIds As ISet(Of Long)
Dim returnValue As ISet(Of String)

returnValue = PriceContextHelper.GetApplicablePriceGroupsForPrice(priceContext, _
    itemCatalogIds)
```

``` csharp
public static ISet<string> GetApplicablePriceGroupsForPrice(
    PriceContext priceContext,
    ISet<long> itemCatalogIds
)
```

``` c++
public:
static ISet<String^>^ GetApplicablePriceGroupsForPrice(
    PriceContext^ priceContext, 
    ISet<long long>^ itemCatalogIds
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - itemCatalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
All applicable price price groups.  

## Remarks

We could have made it an C\# extension. Leave it here for all price context logic.

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

