---
title: PriceContext.PriceCalculationMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: PriceCalculationMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceCalculationMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.pricecalculationmode(v=AX.60)
ms:contentKeyID: 62208468
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceCalculationMode
dev_langs:
- CSharp
- C++
- VB
---

# PriceCalculationMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the price calculation mode for the lines being calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property PriceCalculationMode As PricingCalculationMode
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As PricingCalculationMode

value = instance.PriceCalculationMode

instance.PriceCalculationMode = value
```

``` csharp
public PricingCalculationMode PriceCalculationMode { get; set; }
```

``` c++
public:
property PricingCalculationMode PriceCalculationMode {
    PricingCalculationMode get ();
    void set (PricingCalculationMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

