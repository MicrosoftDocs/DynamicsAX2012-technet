---
title: DiscountableItemGroup Constructor (IEnumerable(SalesLine), PriceContext) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountableItemGroup Constructor (IEnumerable(SalesLine), PriceContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.discountableitemgroup(v=AX.60)
ms:contentKeyID: 62208679
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DiscountableItemGroup Constructor (IEnumerable(SalesLine), PriceContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the DiscountableItemGroup class with the specified SalesLine object included.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lines As IEnumerable(Of SalesLine), _
    priceContext As PriceContext _
)
'Usage
Dim lines As IEnumerable(Of SalesLine)
Dim priceContext As PriceContext

Dim instance As New DiscountableItemGroup(lines, priceContext)
```

``` csharp
public DiscountableItemGroup(
    IEnumerable<SalesLine> lines,
    PriceContext priceContext
)
```

``` c++
public:
DiscountableItemGroup(
    IEnumerable<SalesLine^>^ lines, 
    PriceContext^ priceContext
)
```

#### Parameters

  - lines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[DiscountableItemGroup Overload](discountableitemgroup-constructor-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

