---
title: PriceContextHelper.MatchCalculationMode Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: MatchCalculationMode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.MatchCalculationMode(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscountOfferType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.matchcalculationmode(v=AX.60)
ms:contentKeyID: 62213796
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.MatchCalculationMode
dev_langs:
- CSharp
- C++
- VB
---

# MatchCalculationMode Method

Check whether discount type matches the discount calculation mode in price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function MatchCalculationMode ( _
    priceContext As PriceContext, _
    discountType As PeriodicDiscountOfferType _
) As Boolean
'Usage
Dim priceContext As PriceContext
Dim discountType As PeriodicDiscountOfferType
Dim returnValue As Boolean

returnValue = PriceContextHelper.MatchCalculationMode(priceContext, _
    discountType)
```

``` csharp
public static bool MatchCalculationMode(
    PriceContext priceContext,
    PeriodicDiscountOfferType discountType
)
```

``` c++
public:
static bool MatchCalculationMode(
    PriceContext^ priceContext, 
    PeriodicDiscountOfferType discountType
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - discountType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscountOfferType](periodicdiscountoffertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if discount type matches the discount calculation mode.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

