---
title: ConnectionManager.Connection Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Connection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.Connection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager.connection(v=AX.60)
ms:contentKeyID: 49846019
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.Connection
dev_langs:
- CSharp
- C++
- VB
---

# Connection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the current active connection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Connection As IDatabaseConnection
    Get
'Usage
Dim instance As ConnectionManager
Dim value As IDatabaseConnection

value = instance.Connection
```

``` csharp
public IDatabaseConnection Connection { get; }
```

``` c++
public:
property IDatabaseConnection^ Connection {
    IDatabaseConnection^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [SqlConnection](https://technet.microsoft.com/library/sd2728ad\(v=ax.60\)).  

## See Also

#### Reference

[ConnectionManager Class](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

