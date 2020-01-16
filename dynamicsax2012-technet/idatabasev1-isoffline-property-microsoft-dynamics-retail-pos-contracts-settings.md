---
title: IDatabaseV1.IsOffline Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Settings)
TOCTitle: IsOffline Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.IsOffline
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.settings.idatabasev1.isoffline(v=AX.60)
ms:contentKeyID: 47128615
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Settings.IDatabaseV1.IsOffline
dev_langs:
- CSharp
- C++
- VB
---

# IsOffline Property

Indicates whether the database is currently in Offline mode or not.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Settings](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property IsOffline As Boolean
    Get
'Usage
Dim instance As IDatabaseV1
Dim value As Boolean

value = instance.IsOffline
```

``` csharp
bool IsOffline { get; }
```

``` c++
property bool IsOffline {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IDatabaseV1 Interface](idatabasev1-interface-microsoft-dynamics-retail-pos-contracts-settings.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Settings Namespace](microsoft-dynamics-retail-pos-contracts-settings-namespace.md)

