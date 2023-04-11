---
title: DiscountApplication.Apply Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: Apply Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.Apply(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup[],System.Decimal[],System.Collections.Generic.Stack{Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication},Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountapplication.apply(v=AX.60)
ms:contentKeyID: 65320842
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.Apply
dev_langs:
- CSharp
- C++
- VB
---

# Apply Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Function Apply ( _
    discountableItemGroups As DiscountableItemGroup(), _
    remainingQuantities As Decimal(), _
    appliedDiscounts As Stack(Of AppliedDiscountApplication), _
    priceContext As PriceContext, _
    hasCompetingApplications As Boolean _
) As AppliedDiscountApplication
'Usage
Dim instance As DiscountApplication
Dim discountableItemGroups As DiscountableItemGroup()
Dim remainingQuantities As Decimal()
Dim appliedDiscounts As Stack(Of AppliedDiscountApplication)
Dim priceContext As PriceContext
Dim hasCompetingApplications As Boolean
Dim returnValue As AppliedDiscountApplication

returnValue = instance.Apply(discountableItemGroups, _
    remainingQuantities, appliedDiscounts, _
    priceContext, hasCompetingApplications)
```

``` csharp
public AppliedDiscountApplication Apply(
    DiscountableItemGroup[] discountableItemGroups,
    decimal[] remainingQuantities,
    Stack<AppliedDiscountApplication> appliedDiscounts,
    PriceContext priceContext,
    bool hasCompetingApplications
)
```

``` c++
public:
AppliedDiscountApplication^ Apply(
    array<DiscountableItemGroup^>^ discountableItemGroups, 
    array<Decimal>^ remainingQuantities, 
    Stack<AppliedDiscountApplication^>^ appliedDiscounts, 
    PriceContext^ priceContext, 
    bool hasCompetingApplications
)
```

#### Parameters

  - discountableItemGroups  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\[\]  

<!-- end list -->

  - remainingQuantities  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\[\]  

<!-- end list -->

  - appliedDiscounts  
    Type: [System.Collections.Generic.Stack](https://technet.microsoft.com/library/3278tedw\(v=ax.60\))\<[AppliedDiscountApplication](applieddiscountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - hasCompetingApplications  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication](applieddiscountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

## See Also

#### Reference

[DiscountApplication Class](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

