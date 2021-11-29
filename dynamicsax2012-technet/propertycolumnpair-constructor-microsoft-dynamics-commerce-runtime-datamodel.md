---
title: PropertyColumnPair Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PropertyColumnPair Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.#ctor(System.Reflection.PropertyInfo,Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.propertycolumnpair.propertycolumnpair(v=AX.60)
ms:contentKeyID: 65318015
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PropertyColumnPair Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PropertyColumnPair](propertycolumnpair-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    property As PropertyInfo, _
    column As ColumnAttribute _
)
'Usage
Dim property As PropertyInfo
Dim column As ColumnAttribute

Dim instance As New PropertyColumnPair(property, _
    column)
```

``` csharp
public PropertyColumnPair(
    PropertyInfo property,
    ColumnAttribute column
)
```

``` c++
public:
PropertyColumnPair(
    PropertyInfo^ property, 
    ColumnAttribute^ column
)
```

#### Parameters

  - property  
    Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\))  

<!-- end list -->

  - column  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)  

## See Also

#### Reference

[PropertyColumnPair Class](propertycolumnpair-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

