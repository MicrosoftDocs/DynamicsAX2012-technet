---
title: PriceContext.PriceParameters Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: PriceParameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceParameters
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.priceparameters(v=AX.60)
ms:contentKeyID: 62214021
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.PriceParameters
dev_langs:
- CSharp
- C++
- VB
---

# PriceParameters Property

Gets or sets the configuration of which trade agreement combinations are allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property PriceParameters As PriceParameters
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As PriceParameters

value = instance.PriceParameters

instance.PriceParameters = value
```

``` csharp
public PriceParameters PriceParameters { get; set; }
```

``` c++
public:
property PriceParameters^ PriceParameters {
    PriceParameters^ get ();
    void set (PriceParameters^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

