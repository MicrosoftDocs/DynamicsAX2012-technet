---
title: SqliteDatabaseProvider.ReleaseConnection Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ReleaseConnection Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ReleaseConnection(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.releaseconnection(v=AX.60)
ms:contentKeyID: 65320019
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ReleaseConnection
dev_langs:
- CSharp
- C++
- VB
---

# ReleaseConnection Method

Indicates that a connection string is not going to be used any more.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function ReleaseConnection ( _
    connectionString As String _
) As Boolean
'Usage
Dim instance As SqliteDatabaseProvider
Dim connectionString As String
Dim returnValue As Boolean

returnValue = instance.ReleaseConnection(connectionString)
```

``` csharp
public bool ReleaseConnection(
    string connectionString
)
```

``` c++
public:
bool ReleaseConnection(
    String^ connectionString
)
```

#### Parameters

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the connection string is released successfully otherwise false.  

## Remarks

If the method returns false it just means that some connections cannot be released right now because they are in use.

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

