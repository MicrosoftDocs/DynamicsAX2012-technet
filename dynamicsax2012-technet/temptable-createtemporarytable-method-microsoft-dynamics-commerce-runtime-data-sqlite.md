---
title: TempTable.CreateTemporaryTable Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: CreateTemporaryTable Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.CreateTemporaryTable(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.temptable.createtemporarytable(v=AX.60)
ms:contentKeyID: 65317878
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.CreateTemporaryTable
dev_langs:
- CSharp
- C++
- VB
---

# CreateTemporaryTable Method

Creates a temporary table in the database and copy any rows present in [Rows](datatable-rows-property-microsoft-dynamics-commerce-runtime-data-types.md) to the temporary table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateTemporaryTable ( _
    table As DataTable, _
    connection As IDatabaseConnection _
) As TempTable
'Usage
Dim table As DataTable
Dim connection As IDatabaseConnection
Dim returnValue As TempTable

returnValue = TempTable.CreateTemporaryTable(table, _
    connection)
```

``` csharp
public static TempTable CreateTemporaryTable(
    DataTable table,
    IDatabaseConnection connection
)
```

``` c++
public:
static TempTable^ CreateTemporaryTable(
    DataTable^ table, 
    IDatabaseConnection^ connection
)
```

#### Parameters

  - table  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable](temptable-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)  
An instance of the temporary table.  

## See Also

#### Reference

[TempTable Class](temptable-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

