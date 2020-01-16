---
title: PeriodicDiscount.DiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.discounttype(v=AX.60)
ms:contentKeyID: 49846028
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountType
dev_langs:
- CSharp
- C++
- VB
---

# DiscountType Property

Gets the discount type if this is a quantity discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTTYPE")> _
<DataMemberAttribute> _
Public Property DiscountType As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.DiscountType
```

``` csharp
[ColumnAttribute("DISCOUNTTYPE")]
[DataMemberAttribute]
public int DiscountType { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTTYPE")]
[DataMemberAttribute]
public:
property int DiscountType {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

