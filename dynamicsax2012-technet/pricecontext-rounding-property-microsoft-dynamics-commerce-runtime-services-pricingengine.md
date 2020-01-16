---
title: PriceContext.Rounding Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: Rounding Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.Rounding
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.rounding(v=AX.60)
ms:contentKeyID: 62204371
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.Rounding
dev_langs:
- CSharp
- C++
- VB
---

# Rounding Property

Gets or sets the rounding delegate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property Rounding As RoundingRule
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As RoundingRule

value = instance.Rounding

instance.Rounding = value
```

``` csharp
public RoundingRule Rounding { get; set; }
```

``` c++
public:
property RoundingRule^ Rounding {
    RoundingRule^ get ();
    void set (RoundingRule^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns RoundingRule.  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

