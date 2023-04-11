---
title: DatabaseContext.ConnectionManager Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConnectionManager Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ConnectionManager
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.connectionmanager(v=AX.60)
ms:contentKeyID: 65321597
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ConnectionManager
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionManager Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the connection manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Protected Property ConnectionManager As ConnectionManager
    Get
    Private Set
'Usage
Dim value As ConnectionManager

value = Me.ConnectionManager
```

``` csharp
protected ConnectionManager ConnectionManager { get; private set; }
```

``` c++
protected:
property ConnectionManager^ ConnectionManager {
    ConnectionManager^ get ();
    private: void set (ConnectionManager^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns [ConnectionManager](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

