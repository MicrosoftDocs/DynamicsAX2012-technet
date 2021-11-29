---
title: SqlServerDatabaseProvider.Configure Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: Configure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.Configure(System.Collections.Generic.IDictionary{System.String,System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqlserverdatabaseprovider.configure(v=AX.60)
ms:contentKeyID: 65316567
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlServerDatabaseProvider.Configure
dev_langs:
- CSharp
- C++
- VB
---

# Configure Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Configures the database provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Sub Configure ( _
    configurationDictionary As IDictionary(Of String, String) _
)
'Usage
Dim instance As SqlServerDatabaseProvider
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
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Implements

[IDatabaseProvider.Configure(IDictionary\<String, String\>)](idatabaseprovider-configure-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlServerDatabaseProvider Class](sqlserverdatabaseprovider-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

