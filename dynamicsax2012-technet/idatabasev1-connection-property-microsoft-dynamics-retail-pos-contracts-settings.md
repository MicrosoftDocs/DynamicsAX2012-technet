---
title: IDatabaseV1.Connection Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Settings)
TOCTitle: Connection Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.Connection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.settings.idatabasev1.connection(v=AX.60)
ms:contentKeyID: 47128059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.Connection
dev_langs:
- CSharp
- C++
- VB
---

# Connection Property

Gets the current connection (the store database connection if available, otherwise the local offline connection).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Settings](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Connection As SqlConnection
    Get
'Usage
Dim instance As IDatabaseV1
Dim value As SqlConnection

value = instance.Connection
```

``` csharp
SqlConnection Connection { get; }
```

``` c++
property SqlConnection^ Connection {
    SqlConnection^ get ();
}
```

#### Property Value

Type: [System.Data.SqlClient.SqlConnection](https://technet.microsoft.com/library/sd2728ad\(v=ax.60\))  
The [System.Data.SqlClient.SqlConnection](https://technet.microsoft.com/library/sd2728ad\(v=ax.60\)) value.  

## Remarks

The caller should not dispose the connection because it is owned by the system core.

## See Also

#### Reference

[IDatabaseV1 Interface](idatabasev1-interface-microsoft-dynamics-retail-pos-contracts-settings.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Settings Namespace](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)

