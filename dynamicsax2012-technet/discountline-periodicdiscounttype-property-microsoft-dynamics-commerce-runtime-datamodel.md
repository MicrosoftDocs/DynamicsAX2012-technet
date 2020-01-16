---
title: DiscountLine.PeriodicDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.PeriodicDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.periodicdiscounttype(v=AX.60)
ms:contentKeyID: 49832998
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.PeriodicDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountType Property

The type of a periodic discount, i.e multibuy, mix and match, offer, promotion.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property PeriodicDiscountType As PeriodicDiscountOfferType
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As PeriodicDiscountOfferType

value = instance.PeriodicDiscountType

instance.PeriodicDiscountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public PeriodicDiscountOfferType PeriodicDiscountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
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

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

