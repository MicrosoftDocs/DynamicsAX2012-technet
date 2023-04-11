---
title: DiscountBase.DiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.discounttype(v=AX.60)
ms:contentKeyID: 62214457
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DiscountType
dev_langs:
- CSharp
- C++
- VB
---

# DiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount method type for this offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountType As DiscountMethodType
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As DiscountMethodType

value = instance.DiscountType

instance.DiscountType = value
```

``` csharp
public DiscountMethodType DiscountType { get; set; }
```

``` c++
public:
property DiscountMethodType DiscountType {
    DiscountMethodType get ();
    void set (DiscountMethodType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountMethodType](discountmethodtype-enumeration-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  
Returns [DiscountMethodType](discountmethodtype-enumeration-microsoft-dynamics-commerce-runtime-services-pricingengine.md).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

