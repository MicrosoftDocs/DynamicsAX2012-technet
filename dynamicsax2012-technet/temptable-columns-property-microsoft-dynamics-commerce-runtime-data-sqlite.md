---
title: TempTable.Columns Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.temptable.columns(v=AX.60)
ms:contentKeyID: 65320513
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the column definition for the data table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Columns As ReadOnlyCollection(Of DataColumn)
    Get
'Usage
Dim instance As TempTable
Dim value As ReadOnlyCollection(Of DataColumn)

value = instance.Columns
```

``` csharp
public ReadOnlyCollection<DataColumn> Columns { get; }
```

``` c++
public:
property ReadOnlyCollection<DataColumn^>^ Columns {
    ReadOnlyCollection<DataColumn^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DataColumn](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[TempTable Class](temptable-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

