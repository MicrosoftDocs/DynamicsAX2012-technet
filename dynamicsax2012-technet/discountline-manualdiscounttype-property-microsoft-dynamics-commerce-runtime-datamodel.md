---
title: DiscountLine.ManualDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ManualDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ManualDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.manualdiscounttype(v=AX.60)
ms:contentKeyID: 62211394
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ManualDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# ManualDiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the manual discount type (ie. Total and Line discounts).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("MANUALDISCOUNTTYPE")> _
Public Property ManualDiscountType As ManualDiscountType
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As ManualDiscountType

value = instance.ManualDiscountType

instance.ManualDiscountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("MANUALDISCOUNTTYPE")]
public ManualDiscountType ManualDiscountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"MANUALDISCOUNTTYPE")]
public:
property ManualDiscountType ManualDiscountType {
    ManualDiscountType get ();
    void set (ManualDiscountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType](manualdiscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ManualDiscountType](manualdiscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

