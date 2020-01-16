---
title: ItemBarcode.HasLinkedItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HasLinkedItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.HasLinkedItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.haslinkeditem(v=AX.60)
ms:contentKeyID: 65319932
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.HasLinkedItem
dev_langs:
- CSharp
- C++
- VB
---

# HasLinkedItem Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("HASLINKEDITEM")> _
Public Property HasLinkedItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As Boolean

value = instance.HasLinkedItem
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("HASLINKEDITEM")]
public bool HasLinkedItem { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"HASLINKEDITEM")]
public:
property bool HasLinkedItem {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

