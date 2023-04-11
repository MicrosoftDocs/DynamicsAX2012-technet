---
title: IDatabaseProvider.ExecuteQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.ExecuteQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseprovider.executequery(v=AX.60)
ms:contentKeyID: 65319864
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.ExecuteQuery
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes a command against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function ExecuteQuery ( _
    connection As IDatabaseConnection, _
    query As IDatabaseQuery _
) As IDatabaseResult
'Usage
Dim instance As IDatabaseProvider
Dim connection As IDatabaseConnection
Dim query As IDatabaseQuery
Dim returnValue As IDatabaseResult

returnValue = instance.ExecuteQuery(connection, _
    query)
```

``` csharp
IDatabaseResult ExecuteQuery(
    IDatabaseConnection connection,
    IDatabaseQuery query
)
```

``` c++
IDatabaseResult^ ExecuteQuery(
    IDatabaseConnection^ connection, 
    IDatabaseQuery^ query
)
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

## See Also

#### Reference

[IDatabaseProvider Interface](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

