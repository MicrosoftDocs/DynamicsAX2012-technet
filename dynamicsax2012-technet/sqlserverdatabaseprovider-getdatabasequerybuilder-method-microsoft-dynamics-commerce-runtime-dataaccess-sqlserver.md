---
title: SqlServerDatabaseProvider.GetDatabaseQueryBuilder Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: GetDatabaseQueryBuilder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.GetDatabaseQueryBuilder
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqlserverdatabaseprovider.getdatabasequerybuilder(v=AX.60)
ms:contentKeyID: 65319772
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.GetDatabaseQueryBuilder
dev_langs:
- CSharp
- C++
- VB
---

# GetDatabaseQueryBuilder Method

Returns SQL server implementation of [IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function GetDatabaseQueryBuilder As IDatabaseQueryBuilder
'Usage
Dim instance As SqlServerDatabaseProvider
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
Returns a specific implementation of [IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md).  

#### Implements

[IDatabaseProvider.GetDatabaseQueryBuilder()](idatabaseprovider-getdatabasequerybuilder-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlServerDatabaseProvider Class](sqlserverdatabaseprovider-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

