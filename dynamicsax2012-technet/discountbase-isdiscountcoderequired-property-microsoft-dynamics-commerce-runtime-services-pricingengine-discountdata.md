---
title: DiscountBase.IsDiscountCodeRequired Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: IsDiscountCodeRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountCodeRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.isdiscountcoderequired(v=AX.60)
ms:contentKeyID: 62208284
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.IsDiscountCodeRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountCodeRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether or not a discount code is required to trigger this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property IsDiscountCodeRequired As Boolean
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As Boolean

value = instance.IsDiscountCodeRequired

instance.IsDiscountCodeRequired = value
```

``` csharp
public bool IsDiscountCodeRequired { get; set; }
```

``` c++
public:
property bool IsDiscountCodeRequired {
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

