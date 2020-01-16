---
title: IDatabaseV1.OfflineConnection Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Settings)
TOCTitle: OfflineConnection Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.OfflineConnection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.settings.idatabasev1.offlineconnection(v=AX.60)
ms:contentKeyID: 47129185
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.OfflineConnection
dev_langs:
- CSharp
- C++
- VB
---

# OfflineConnection Property

Gets the offline connection if available, otherwise null.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Settings](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property OfflineConnection As SqlConnection
    Get
'Usage
Dim instance As IDatabaseV1
Dim value As SqlConnection

value = instance.OfflineConnection
```

``` csharp
SqlConnection OfflineConnection { get; }
```

``` c++
property SqlConnection^ OfflineConnection {
    SqlConnection^ get ();
}
```

#### Property Value

Type: [System.Data.SqlClient.SqlConnection](https://technet.microsoft.com/library/sd2728ad\(v=ax.60\))  
The [System.Data.SqlClient.SqlConnection](https://technet.microsoft.com/library/sd2728ad\(v=ax.60\)) value.  

## Remarks

Caller should not dispose the connection because it is owned by the system core.

## See Also

#### Reference

[IDatabaseV1 Interface](idatabasev1-interface-microsoft-dynamics-retail-pos-contracts-settings.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Settings Namespace](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)

