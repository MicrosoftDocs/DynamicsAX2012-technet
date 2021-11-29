---
title: DiscountableItemGroup Constructor (SalesLine, PriceContext) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountableItemGroup Constructor (SalesLine, PriceContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.discountableitemgroup(v=AX.60)
ms:contentKeyID: 62211428
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DiscountableItemGroup Constructor (SalesLine, PriceContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the DiscountableItemGroup class with the specified SalesLine object included.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    line As SalesLine, _
    priceContext As PriceContext _
)
'Usage
Dim line As SalesLine
Dim priceContext As PriceContext

Dim instance As New DiscountableItemGroup(line, priceContext)
```

``` csharp
public DiscountableItemGroup(
    SalesLine line,
    PriceContext priceContext
)
```

``` c++
public:
DiscountableItemGroup(
    SalesLine^ line, 
    PriceContext^ priceContext
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[DiscountableItemGroup Overload](discountableitemgroup-constructor-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

