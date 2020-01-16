---
title: DiscountLine.IsCompoundable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCompoundable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.IsCompoundable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.iscompoundable(v=AX.60)
ms:contentKeyID: 49839572
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.IsCompoundable
dev_langs:
- CSharp
- C++
- VB
---

# IsCompoundable Property

Gets or sets whether this discount line is of a type that can be repeated compounded

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCompoundable As Boolean
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Boolean

value = instance.IsCompoundable

instance.IsCompoundable = value
```

``` csharp
[DataMemberAttribute]
public bool IsCompoundable { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCompoundable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## Remarks

For example, "amount off" or "percent off" discounts can be compounded repeatedly, whereas "price amount" discounts can not.

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

