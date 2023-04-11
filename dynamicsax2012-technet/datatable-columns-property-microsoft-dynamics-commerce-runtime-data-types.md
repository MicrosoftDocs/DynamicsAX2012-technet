---
title: DataTable.Columns Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datatable.columns(v=AX.60)
ms:contentKeyID: 65322624
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of columns for this table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Columns As DataColumnCollection
    Get
    Private Set
'Usage
Dim instance As DataTable
Dim value As DataColumnCollection

value = instance.Columns
```

``` csharp
public DataColumnCollection Columns { get; private set; }
```

``` c++
public:
property DataColumnCollection^ Columns {
    DataColumnCollection^ get ();
    private: void set (DataColumnCollection^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumnCollection](datacolumncollection-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataColumnCollection](datacolumncollection-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[DataTable Class](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

