---
title: RetailDiscount.PeriodicDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PeriodicDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.periodicdiscounttype(v=AX.60)
ms:contentKeyID: 62214689
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PeriodicDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of this discount (offer, quantity, or mix and match).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PERIODICDISCOUNTTYPE")> _
Public Property PeriodicDiscountType As PeriodicDiscountOfferType
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As PeriodicDiscountOfferType

value = instance.PeriodicDiscountType

instance.PeriodicDiscountType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERIODICDISCOUNTTYPE")]
public PeriodicDiscountOfferType PeriodicDiscountType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERIODICDISCOUNTTYPE")]
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

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

