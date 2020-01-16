---
title: PriceContextHelper.IsDiscountAllowed Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: IsDiscountAllowed Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.IsDiscountAllowed(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.isdiscountallowed(v=AX.60)
ms:contentKeyID: 62214684
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.IsDiscountAllowed
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountAllowed Method

Check whether the discount is allowed for the item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsDiscountAllowed ( _
    priceContext As PriceContext, _
    itemId As String _
) As Boolean
'Usage
Dim priceContext As PriceContext
Dim itemId As String
Dim returnValue As Boolean

returnValue = PriceContextHelper.IsDiscountAllowed(priceContext, _
    itemId)
```

``` csharp
public static bool IsDiscountAllowed(
    PriceContext priceContext,
    string itemId
)
```

``` c++
public:
static bool IsDiscountAllowed(
    PriceContext^ priceContext, 
    String^ itemId
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the discount is allowed for the item, otherwise false.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

