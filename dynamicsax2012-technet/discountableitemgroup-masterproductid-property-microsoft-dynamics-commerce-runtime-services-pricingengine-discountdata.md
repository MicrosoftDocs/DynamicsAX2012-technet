---
title: DiscountableItemGroup.MasterProductId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: MasterProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.MasterProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.masterproductid(v=AX.60)
ms:contentKeyID: 62213624
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.MasterProductId
dev_langs:
- CSharp
- C++
- VB
---

# MasterProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets product id or the master product id of the variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property MasterProductId As Long
    Get
'Usage
Dim instance As DiscountableItemGroup
Dim value As Long

value = instance.MasterProductId
```

``` csharp
public long MasterProductId { get; }
```

``` c++
public:
property long long MasterProductId {
    long long get ();
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## Remarks

This is RecId in EcoResProduct table.

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

