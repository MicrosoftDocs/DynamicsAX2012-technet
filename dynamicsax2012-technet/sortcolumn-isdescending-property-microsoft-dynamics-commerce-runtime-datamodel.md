---
title: SortColumn.IsDescending Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDescending Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.IsDescending
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortcolumn.isdescending(v=AX.60)
ms:contentKeyID: 65318975
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.IsDescending
dev_langs:
- CSharp
- C++
- VB
---

# IsDescending Property

Gets or sets a value indicating whether this column is to be sorted in descending order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsDescending As Boolean
    Get
    Set
'Usage
Dim instance As SortColumn
Dim value As Boolean

value = instance.IsDescending

instance.IsDescending = value
```

``` csharp
[DataMemberAttribute]
public bool IsDescending { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsDescending {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true, the column is to be sorted in descending order. Otherwise, ascending order.  

## See Also

#### Reference

[SortColumn Class](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

