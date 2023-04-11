---
title: SqliteDatabaseProvider.GetConnection Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: GetConnection Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetConnection(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.getconnection(v=AX.60)
ms:contentKeyID: 65322048
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetConnection
dev_langs:
- CSharp
- C++
- VB
---

# GetConnection Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a connection to operate against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetConnection ( _
    connectionString As String _
) As IDatabaseConnection
'Usage
Dim instance As SqliteDatabaseProvider
Dim connectionString As String
Dim returnValue As IDatabaseConnection

returnValue = instance.GetConnection(connectionString)
```

``` csharp
public IDatabaseConnection GetConnection(
    string connectionString
)
```

``` c++
public:
virtual IDatabaseConnection^ GetConnection(
    String^ connectionString
) sealed
```

#### Parameters

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  
A connection to operate against the database.  

#### Implements

[IDatabaseProvider.GetConnection(String)](idatabaseprovider-getconnection-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

