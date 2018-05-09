---
title: SqlServerDatabaseProvider.GetConnection Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: GetConnection Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.GetConnection(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqlserverdatabaseprovider.getconnection(v=AX.60)
ms:contentKeyID: 65316126
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.GetConnection
dev_langs:
- CSharp
- C++
- VB
---

# GetConnection Method

Gets a connection to operate against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function GetConnection ( _
    connectionString As String _
) As IDatabaseConnection
'Usage
Dim instance As SqlServerDatabaseProvider
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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  
A connection to operate against the database.  

#### Implements

[IDatabaseProvider.GetConnection(String)](idatabaseprovider-getconnection-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlServerDatabaseProvider Class](sqlserverdatabaseprovider-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

