---
title: DiscountBase.CloneDiscountItem Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: CloneDiscountItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.CloneDiscountItem(Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.clonediscountitem(v=AX.60)
ms:contentKeyID: 62208483
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.CloneDiscountItem
dev_langs:
- CSharp
- C++
- VB
---

# CloneDiscountItem Method

Creates a new DiscountLine that is a copy of the specified line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CloneDiscountItem ( _
    original As DiscountLine _
) As DiscountLine
'Usage
Dim original As DiscountLine
Dim returnValue As DiscountLine

returnValue = DiscountBase.CloneDiscountItem(original)
```

``` csharp
protected static DiscountLine CloneDiscountItem(
    DiscountLine original
)
```

``` c++
protected:
static DiscountLine^ CloneDiscountItem(
    DiscountLine^ original
)
```

#### Parameters

  - original  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The new discount line.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

