---
title: IDatabaseProvider.GetConnection Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetConnection Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.GetConnection(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseprovider.getconnection(v=AX.60)
ms:contentKeyID: 65315686
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.GetConnection
dev_langs:
- CSharp
- C++
- VB
---

# GetConnection Method

Gets a connection to operate against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetConnection ( _
    connectionString As String _
) As IDatabaseConnection
'Usage
Dim instance As IDatabaseProvider
Dim connectionString As String
Dim returnValue As IDatabaseConnection

returnValue = instance.GetConnection(connectionString)
```

``` csharp
IDatabaseConnection GetConnection(
    string connectionString
)
```

``` c++
IDatabaseConnection^ GetConnection(
    String^ connectionString
)
```

#### Parameters

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  
A connection to operate against the database.  

## See Also

#### Reference

[IDatabaseProvider Interface](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

