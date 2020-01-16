---
title: EntityTypeCache.GetPropertyColumnAttribute Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetPropertyColumnAttribute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetPropertyColumnAttribute(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.entitytypecache.getpropertycolumnattribute(v=AX.60)
ms:contentKeyID: 65320869
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetPropertyColumnAttribute
dev_langs:
- CSharp
- C++
- VB
---

# GetPropertyColumnAttribute Method

Gets the property column attribute by column name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetPropertyColumnAttribute ( _
    columnName As String _
) As ColumnAttribute
'Usage
Dim instance As EntityTypeCache
Dim columnName As String
Dim returnValue As ColumnAttribute

returnValue = instance.GetPropertyColumnAttribute(columnName)
```

``` csharp
public ColumnAttribute GetPropertyColumnAttribute(
    string columnName
)
```

``` c++
public:
ColumnAttribute^ GetPropertyColumnAttribute(
    String^ columnName
)
```

#### Parameters

  - columnName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)  
The column attribute specified on the property or null if the attribute is not present in the property.  

## See Also

#### Reference

[EntityTypeCache Class](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

