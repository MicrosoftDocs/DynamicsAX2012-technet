---
title: PropertyColumnPair.Column Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Column Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.Column
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.propertycolumnpair.column(v=AX.60)
ms:contentKeyID: 65317450
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.Column
dev_langs:
- CSharp
- C++
- VB
---

# Column Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the column information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Column As ColumnAttribute
    Get
    Private Set
'Usage
Dim instance As PropertyColumnPair
Dim value As ColumnAttribute

value = instance.Column
```

``` csharp
public ColumnAttribute Column { get; private set; }
```

``` c++
public:
property ColumnAttribute^ Column {
    ColumnAttribute^ get ();
    private: void set (ColumnAttribute^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)  
Returns [ColumnAttribute](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md).  

## See Also

#### Reference

[PropertyColumnPair Class](propertycolumnpair-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

