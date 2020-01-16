---
title: PeriodicDiscount.PeriodicDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.PeriodicDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.periodicdiscounttype(v=AX.60)
ms:contentKeyID: 49832001
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.PeriodicDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountType Property

Gets the type of this discount (offer, quantity, or mix and match).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PERIODICDISCOUNTTYPE")> _
Public Property PeriodicDiscountType As PeriodicDiscountOfferType
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As PeriodicDiscountOfferType

value = instance.PeriodicDiscountType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERIODICDISCOUNTTYPE")]
public PeriodicDiscountOfferType PeriodicDiscountType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERIODICDISCOUNTTYPE")]
public:
property PeriodicDiscountOfferType PeriodicDiscountType {
    PeriodicDiscountOfferType get ();
    internal: void set (PeriodicDiscountOfferType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscountOfferType](periodicdiscountoffertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PeriodicDiscountOfferType](periodicdiscountoffertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

