---
title: DiscountBase.ShouldCountNonDiscountItems Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ShouldCountNonDiscountItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ShouldCountNonDiscountItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.shouldcountnondiscountitems(v=AX.60)
ms:contentKeyID: 62203744
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ShouldCountNonDiscountItems
dev_langs:
- CSharp
- C++
- VB
---

# ShouldCountNonDiscountItems Property

Gets or sets a value indicating whether non-discount items contribute to threshold amount trigger.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ShouldCountNonDiscountItems As Boolean
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As Boolean

value = instance.ShouldCountNonDiscountItems

instance.ShouldCountNonDiscountItems = value
```

``` csharp
public bool ShouldCountNonDiscountItems { get; set; }
```

``` c++
public:
property bool ShouldCountNonDiscountItems {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

