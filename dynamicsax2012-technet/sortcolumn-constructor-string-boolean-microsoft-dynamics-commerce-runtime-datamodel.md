---
title: SortColumn Constructor (String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SortColumn Constructor (String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.#ctor(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortcolumn.sortcolumn(v=AX.60)
ms:contentKeyID: 65318585
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SortColumn Constructor (String, Boolean)

Initializes a new instance of the [SortColumn](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    columnName As String, _
    isDescending As Boolean _
)
'Usage
Dim columnName As String
Dim isDescending As Boolean

Dim instance As New SortColumn(columnName, _
    isDescending)
```

``` csharp
public SortColumn(
    string columnName,
    bool isDescending
)
```

``` c++
public:
SortColumn(
    String^ columnName, 
    bool isDescending
)
```

#### Parameters

  - columnName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isDescending  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SortColumn Class](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SortColumn Overload](sortcolumn-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

