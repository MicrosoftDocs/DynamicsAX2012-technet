---
title: DiscountBase.GenerateDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GenerateDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GenerateDiscountLines(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup[],Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.generatediscountlines(v=AX.60)
ms:contentKeyID: 65320882
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GenerateDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# GenerateDiscountLines Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Sub GenerateDiscountLines ( _
    appliedDiscountApplication As AppliedDiscountApplication, _
    discountableItemGroups As DiscountableItemGroup(), _
    priceContext As PriceContext _
)
'Usage
Dim instance As DiscountBase
Dim appliedDiscountApplication As AppliedDiscountApplication
Dim discountableItemGroups As DiscountableItemGroup()
Dim priceContext As PriceContext

instance.GenerateDiscountLines(appliedDiscountApplication, _
    discountableItemGroups, priceContext)
```

``` csharp
public abstract void GenerateDiscountLines(
    AppliedDiscountApplication appliedDiscountApplication,
    DiscountableItemGroup[] discountableItemGroups,
    PriceContext priceContext
)
```

``` c++
public:
virtual void GenerateDiscountLines(
    AppliedDiscountApplication^ appliedDiscountApplication, 
    array<DiscountableItemGroup^>^ discountableItemGroups, 
    PriceContext^ priceContext
) abstract
```

#### Parameters

  - appliedDiscountApplication  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication](applieddiscountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

<!-- end list -->

  - discountableItemGroups  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\[\]  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

