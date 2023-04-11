---
title: Item.NoDiscountAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NoDiscountAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.NoDiscountAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.nodiscountallowed(v=AX.60)
ms:contentKeyID: 49847854
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.NoDiscountAllowed
dev_langs:
- CSharp
- C++
- VB
---

# NoDiscountAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether discounts should apply to this item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NODISCOUNTALLOWED")> _
<DataMemberAttribute> _
Public Property NoDiscountAllowed As Boolean
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Boolean

value = instance.NoDiscountAllowed
```

``` csharp
[ColumnAttribute("NODISCOUNTALLOWED")]
[DataMemberAttribute]
public bool NoDiscountAllowed { get; internal set; }
```

``` c++
[ColumnAttribute(L"NODISCOUNTALLOWED")]
[DataMemberAttribute]
public:
property bool NoDiscountAllowed {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

