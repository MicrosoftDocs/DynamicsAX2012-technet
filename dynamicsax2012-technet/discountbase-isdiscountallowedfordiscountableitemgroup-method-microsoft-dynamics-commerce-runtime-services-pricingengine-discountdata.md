---
title: DiscountBase.IsDiscountAllowedForDiscountableItemGroup Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: IsDiscountAllowedForDiscountableItemGroup Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountAllowedForDiscountableItemGroup(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.isdiscountallowedfordiscountableitemgroup(v=AX.60)
ms:contentKeyID: 62211704
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountAllowedForDiscountableItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountAllowedForDiscountableItemGroup Method

Determines whether the specified item group is eligible for discounts (based on the NoDiscount flag).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function IsDiscountAllowedForDiscountableItemGroup ( _
    discountableItemGroup As DiscountableItemGroup _
) As Boolean
'Usage
Dim discountableItemGroup As DiscountableItemGroup
Dim returnValue As Boolean

returnValue = DiscountBase.IsDiscountAllowedForDiscountableItemGroup(discountableItemGroup)
```

``` csharp
protected static bool IsDiscountAllowedForDiscountableItemGroup(
    DiscountableItemGroup discountableItemGroup
)
```

``` c++
protected:
static bool IsDiscountAllowedForDiscountableItemGroup(
    DiscountableItemGroup^ discountableItemGroup
)
```

#### Parameters

  - discountableItemGroup  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the item may be discounted, false otherwise.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

