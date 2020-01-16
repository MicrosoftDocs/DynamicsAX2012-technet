---
title: DiscountParameters.CreateAndInitialize Method (PriceParameters) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CreateAndInitialize Method (PriceParameters)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.CreateAndInitialize(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountparameters.createandinitialize(v=AX.60)
ms:contentKeyID: 62212788
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateAndInitialize Method (PriceParameters)

Create a new DiscountParameters object from the passed in data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateAndInitialize ( _
    priceParameters As PriceParameters _
) As DiscountParameters
'Usage
Dim priceParameters As PriceParameters
Dim returnValue As DiscountParameters

returnValue = DiscountParameters.CreateAndInitialize(priceParameters)
```

``` csharp
public static DiscountParameters CreateAndInitialize(
    PriceParameters priceParameters
)
```

``` c++
public:
static DiscountParameters^ CreateAndInitialize(
    PriceParameters^ priceParameters
)
```

#### Parameters

  - priceParameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  
Newly fetched and initialized DiscountParameters object.  

## See Also

#### Reference

[DiscountParameters Class](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[CreateAndInitialize Overload](discountparameters-createandinitialize-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

