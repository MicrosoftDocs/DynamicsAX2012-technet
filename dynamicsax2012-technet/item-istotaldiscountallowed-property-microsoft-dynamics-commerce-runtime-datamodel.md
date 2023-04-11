---
title: Item.IsTotalDiscountAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTotalDiscountAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.IsTotalDiscountAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.istotaldiscountallowed(v=AX.60)
ms:contentKeyID: 49821750
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.IsTotalDiscountAllowed
dev_langs:
- CSharp
- C++
- VB
---

# IsTotalDiscountAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this item is eligible to be part of a total discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ENDDISC")> _
<DataMemberAttribute> _
Public Property IsTotalDiscountAllowed As Boolean
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Boolean

value = instance.IsTotalDiscountAllowed
```

``` csharp
[ColumnAttribute("ENDDISC")]
[DataMemberAttribute]
public bool IsTotalDiscountAllowed { get; internal set; }
```

``` c++
[ColumnAttribute(L"ENDDISC")]
[DataMemberAttribute]
public:
property bool IsTotalDiscountAllowed {
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

