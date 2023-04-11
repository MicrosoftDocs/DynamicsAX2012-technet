---
title: SqliteDatabaseProvider.GetDatabaseQueryBuilder Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: GetDatabaseQueryBuilder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetDatabaseQueryBuilder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.getdatabasequerybuilder(v=AX.60)
ms:contentKeyID: 65323037
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetDatabaseQueryBuilder
dev_langs:
- CSharp
- C++
- VB
---

# GetDatabaseQueryBuilder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the database query builder.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetDatabaseQueryBuilder As IDatabaseQueryBuilder
'Usage
Dim instance As SqliteDatabaseProvider
Dim returnValue As IDatabaseQueryBuilder

returnValue = instance.GetDatabaseQueryBuilder()
```

``` csharp
public IDatabaseQueryBuilder GetDatabaseQueryBuilder()
```

``` c++
public:
virtual IDatabaseQueryBuilder^ GetDatabaseQueryBuilder() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  
The database query builder.  

#### Implements

[IDatabaseProvider.GetDatabaseQueryBuilder()](idatabaseprovider-getdatabasequerybuilder-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

