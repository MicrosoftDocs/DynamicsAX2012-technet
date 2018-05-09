---
title: DiscountBase.PeriodicDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: PeriodicDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.PeriodicDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.periodicdiscounttype(v=AX.60)
ms:contentKeyID: 62210738
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.PeriodicDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountType Property

Gets or sets the type of discount (mix and match, quantity, threshold, etc.).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property PeriodicDiscountType As PeriodicDiscountOfferType
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As PeriodicDiscountOfferType

value = instance.PeriodicDiscountType

instance.PeriodicDiscountType = value
```

``` csharp
public PeriodicDiscountOfferType PeriodicDiscountType { get; set; }
```

``` c++
public:
property PeriodicDiscountOfferType PeriodicDiscountType {
    PeriodicDiscountOfferType get ();
    void set (PeriodicDiscountOfferType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscountOfferType](periodicdiscountoffertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PeriodicDiscountOfferType](periodicdiscountoffertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

