---
title: SortingInfo Constructor (String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SortingInfo Constructor (String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.#ctor(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.sortinginfo.sortinginfo(v=AX.60)
ms:contentKeyID: 65319595
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SortingInfo Constructor (String, Boolean)

Initializes a new instance of the [SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

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

Dim instance As New SortingInfo(columnName, _
    isDescending)
```

``` csharp
public SortingInfo(
    string columnName,
    bool isDescending
)
```

``` c++
public:
SortingInfo(
    String^ columnName, 
    bool isDescending
)
```

#### Parameters

  - columnName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isDescending  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SortingInfo Class](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SortingInfo Overload](sortinginfo-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

