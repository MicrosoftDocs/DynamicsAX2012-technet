---
title: Item.AllocateMarkup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllocateMarkup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.AllocateMarkup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.allocatemarkup(v=AX.60)
ms:contentKeyID: 49851996
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.AllocateMarkup
dev_langs:
- CSharp
- C++
- VB
---

# AllocateMarkup Property

Gets a value indicating whether markup should be allocated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOCATEMARKUP")> _
<DataMemberAttribute> _
Public Property AllocateMarkup As Boolean
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Boolean

value = instance.AllocateMarkup
```

``` csharp
[ColumnAttribute("ALLOCATEMARKUP")]
[DataMemberAttribute]
public bool AllocateMarkup { get; internal set; }
```

``` c++
[ColumnAttribute(L"ALLOCATEMARKUP")]
[DataMemberAttribute]
public:
property bool AllocateMarkup {
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

