---
title: DiscountBase.GetFirstMatchingLineForItem Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetFirstMatchingLineForItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetFirstMatchingLineForItem(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.getfirstmatchinglineforitem(v=AX.60)
ms:contentKeyID: 62210333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetFirstMatchingLineForItem
dev_langs:
- CSharp
- C++
- VB
---

# GetFirstMatchingLineForItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines if the specified item is valid for the specified discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function GetFirstMatchingLineForItem ( _
    discountableItemGroup As DiscountableItemGroup, _
    discountLines As IEnumerable(Of RetailDiscountLine) _
) As RetailDiscountLine
'Usage
Dim discountableItemGroup As DiscountableItemGroup
Dim discountLines As IEnumerable(Of RetailDiscountLine)
Dim returnValue As RetailDiscountLine

returnValue = Me.GetFirstMatchingLineForItem(discountableItemGroup, _
    discountLines)
```

``` csharp
protected RetailDiscountLine GetFirstMatchingLineForItem(
    DiscountableItemGroup discountableItemGroup,
    IEnumerable<RetailDiscountLine> discountLines
)
```

``` c++
protected:
RetailDiscountLine^ GetFirstMatchingLineForItem(
    DiscountableItemGroup^ discountableItemGroup, 
    IEnumerable<RetailDiscountLine^>^ discountLines
)
```

#### Parameters

  - discountableItemGroup  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

<!-- end list -->

  - discountLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
True if the item is valid, false otherwise.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

