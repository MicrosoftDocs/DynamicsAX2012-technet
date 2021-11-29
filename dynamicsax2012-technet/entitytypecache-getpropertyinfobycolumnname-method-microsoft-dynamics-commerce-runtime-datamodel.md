---
title: EntityTypeCache.GetPropertyInfoByColumnName Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetPropertyInfoByColumnName Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetPropertyInfoByColumnName(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.entitytypecache.getpropertyinfobycolumnname(v=AX.60)
ms:contentKeyID: 65319915
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetPropertyInfoByColumnName
dev_langs:
- CSharp
- C++
- VB
---

# GetPropertyInfoByColumnName Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the [PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\)) for a property of the entity that specifies [ColumnAttribute](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetPropertyInfoByColumnName ( _
    columnName As String _
) As PropertyInfo
'Usage
Dim instance As EntityTypeCache
Dim columnName As String
Dim returnValue As PropertyInfo

returnValue = instance.GetPropertyInfoByColumnName(columnName)
```

``` csharp
public PropertyInfo GetPropertyInfoByColumnName(
    string columnName
)
```

``` c++
public:
PropertyInfo^ GetPropertyInfoByColumnName(
    String^ columnName
)
```

#### Parameters

  - columnName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\))  
The [PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\)) for the property that specifies the column described by columnName.  

## See Also

#### Reference

[EntityTypeCache Class](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

