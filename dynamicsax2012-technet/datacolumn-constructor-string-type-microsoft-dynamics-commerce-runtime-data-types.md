---
title: DataColumn Constructor (String, Type) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DataColumn Constructor (String, Type)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.#ctor(System.String,System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumn.datacolumn(v=AX.60)
ms:contentKeyID: 65318628
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataColumn Constructor (String, Type)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DataColumn](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    columnName As String, _
    type As Type _
)
'Usage
Dim columnName As String
Dim type As Type

Dim instance As New DataColumn(columnName, _
    type)
```

``` csharp
public DataColumn(
    string columnName,
    Type type
)
```

``` c++
public:
DataColumn(
    String^ columnName, 
    Type^ type
)
```

#### Parameters

  - columnName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - type  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

## See Also

#### Reference

[DataColumn Class](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)

[DataColumn Overload](datacolumn-constructor-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

