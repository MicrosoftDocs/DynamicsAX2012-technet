---
title: DiscountableItemGroup.DiscountLineQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountLineQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.DiscountLineQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.discountlinequantities(v=AX.60)
ms:contentKeyID: 62213471
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.DiscountLineQuantities
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineQuantities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of DiscountLineQuantity objects for this group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property DiscountLineQuantities As IEnumerable(Of DiscountLineQuantity)
    Get
'Usage
Dim instance As DiscountableItemGroup
Dim value As IEnumerable(Of DiscountLineQuantity)

value = instance.DiscountLineQuantities
```

``` csharp
public IEnumerable<DiscountLineQuantity> DiscountLineQuantities { get; }
```

``` c++
public:
property IEnumerable<DiscountLineQuantity^>^ DiscountLineQuantities {
    IEnumerable<DiscountLineQuantity^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DiscountLineQuantity](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

