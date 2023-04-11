---
title: DataColumnCollection.Add Method (String, Type) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Add Method (String, Type)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumnCollection.Add(System.String,System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumncollection.add(v=AX.60)
ms:contentKeyID: 65320181
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Add Method (String, Type)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds a column to this collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Add ( _
    columnName As String, _
    type As Type _
) As DataColumn
'Usage
Dim instance As DataColumnCollection
Dim columnName As String
Dim type As Type
Dim returnValue As DataColumn

returnValue = instance.Add(columnName, _
    type)
```

``` csharp
public DataColumn Add(
    string columnName,
    Type type
)
```

``` c++
public:
DataColumn^ Add(
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

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The added data column.  

## See Also

#### Reference

[DataColumnCollection Class](datacolumncollection-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Add Overload](datacolumncollection-add-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

