---
title: DiscountableItemGroup.ExtendedProperties Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ExtendedProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.ExtendedProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.extendedproperties(v=AX.60)
ms:contentKeyID: 62211540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.ExtendedProperties
dev_langs:
- CSharp
- C++
- VB
---

# ExtendedProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Item extended properties for this item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ExtendedProperties As Item
    Get
    Set
'Usage
Dim instance As DiscountableItemGroup
Dim value As Item

value = instance.ExtendedProperties

instance.ExtendedProperties = value
```

``` csharp
public Item ExtendedProperties { get; set; }
```

``` c++
public:
property Item^ ExtendedProperties {
    Item^ get ();
    void set (Item^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

