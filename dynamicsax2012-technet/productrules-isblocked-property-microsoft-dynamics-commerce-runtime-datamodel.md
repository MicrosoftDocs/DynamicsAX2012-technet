---
title: ProductRules.IsBlocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsBlocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsBlocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.isblocked(v=AX.60)
ms:contentKeyID: 62211705
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsBlocked
dev_langs:
- CSharp
- C++
- VB
---

# IsBlocked Property

Gets a value indicating whether this item is blocked.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BLOCKEDONPOS")> _
Public Property IsBlocked As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.IsBlocked
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BLOCKEDONPOS")]
public bool IsBlocked { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BLOCKEDONPOS")]
public:
property bool IsBlocked {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

