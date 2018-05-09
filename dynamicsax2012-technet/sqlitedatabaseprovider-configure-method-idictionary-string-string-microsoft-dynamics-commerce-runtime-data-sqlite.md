---
title: SqliteDatabaseProvider.Configure Method (IDictionary(String, String)) (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: Configure Method (IDictionary(String, String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.Configure(System.Collections.Generic.IDictionary{System.String,System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.configure(v=AX.60)
ms:contentKeyID: 65317943
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Configure Method (IDictionary(String, String))

Configures the database provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Sub Configure ( _
    configurationDictionary As IDictionary(Of String, String) _
)
'Usage
Dim instance As SqliteDatabaseProvider
Dim configurationDictionary As IDictionary(Of String, String)

instance.Configure(configurationDictionary)
```

``` csharp
public void Configure(
    IDictionary<string, string> configurationDictionary
)
```

``` c++
public:
virtual void Configure(
    IDictionary<String^, String^>^ configurationDictionary
) sealed
```

#### Parameters

  - configurationDictionary  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Implements

[IDatabaseProvider.Configure(IDictionary\<String, String\>)](idatabaseprovider-configure-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Configure Overload](sqlitedatabaseprovider-configure-method-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

