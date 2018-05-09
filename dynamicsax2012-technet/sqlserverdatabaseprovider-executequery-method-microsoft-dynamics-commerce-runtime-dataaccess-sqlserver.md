---
title: SqlServerDatabaseProvider.ExecuteQuery Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: ExecuteQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.ExecuteQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqlserverdatabaseprovider.executequery(v=AX.60)
ms:contentKeyID: 65322682
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.ExecuteQuery
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteQuery Method

Executes a command against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteQuery ( _
    connection As IDatabaseConnection, _
    query As IDatabaseQuery _
) As IDatabaseResult
'Usage
Dim instance As SqlServerDatabaseProvider
Dim connection As IDatabaseConnection
Dim query As IDatabaseQuery
Dim returnValue As IDatabaseResult

returnValue = instance.ExecuteQuery(connection, _
    query)
```

``` csharp
public IDatabaseResult ExecuteQuery(
    IDatabaseConnection connection,
    IDatabaseQuery query
)
```

``` c++
public:
virtual IDatabaseResult^ ExecuteQuery(
    IDatabaseConnection^ connection, 
    IDatabaseQuery^ query
) sealed
```

#### Parameters

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)  
The database result object containing the results for the executed command.  

#### Implements

[IDatabaseProvider.ExecuteQuery(IDatabaseConnection, IDatabaseQuery)](idatabaseprovider-executequery-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlServerDatabaseProvider Class](sqlserverdatabaseprovider-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

