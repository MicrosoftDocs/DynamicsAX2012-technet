---
title: PriceContext.DiscountCalculationMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: DiscountCalculationMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.DiscountCalculationMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.discountcalculationmode(v=AX.60)
ms:contentKeyID: 62205371
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.DiscountCalculationMode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCalculationMode Property

Gets or sets the discount calculation mode for the lines being calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountCalculationMode As DiscountCalculationMode
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As DiscountCalculationMode

value = instance.DiscountCalculationMode

instance.DiscountCalculationMode = value
```

``` csharp
public DiscountCalculationMode DiscountCalculationMode { get; set; }
```

``` c++
public:
property DiscountCalculationMode DiscountCalculationMode {
    DiscountCalculationMode get ();
    void set (DiscountCalculationMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

