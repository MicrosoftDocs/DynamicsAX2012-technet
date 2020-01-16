---
title: DiscountBase.IsItemValidForLine Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: IsItemValidForLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsItemValidForLine(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.isitemvalidforline(v=AX.60)
ms:contentKeyID: 62214668
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsItemValidForLine
dev_langs:
- CSharp
- C++
- VB
---

# IsItemValidForLine Method

Determines if the specified item is valid for the specified discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function IsItemValidForLine ( _
    discountableItemGroup As DiscountableItemGroup, _
    discountLine As RetailDiscountLine _
) As Boolean
'Usage
Dim discountableItemGroup As DiscountableItemGroup
Dim discountLine As RetailDiscountLine
Dim returnValue As Boolean

returnValue = Me.IsItemValidForLine(discountableItemGroup, _
    discountLine)
```

``` csharp
protected bool IsItemValidForLine(
    DiscountableItemGroup discountableItemGroup,
    RetailDiscountLine discountLine
)
```

``` c++
protected:
bool IsItemValidForLine(
    DiscountableItemGroup^ discountableItemGroup, 
    RetailDiscountLine^ discountLine
)
```

#### Parameters

  - discountableItemGroup  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

<!-- end list -->

  - discountLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the item is valid, false otherwise.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

