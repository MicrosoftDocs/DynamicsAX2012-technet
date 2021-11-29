---
title: ConnectionManager Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConnectionManager Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager(v=AX.60)
ms:contentKeyID: 49819643
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionManager Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Responsible for managing the lifetime of current active connection and encapsulates the logic necessary to failover to the offline database if available.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ConnectionManager _
    Implements IDisposable
'Usage
Dim instance As ConnectionManager
```

``` csharp
public sealed class ConnectionManager : IDisposable
```

``` c++
public ref class ConnectionManager sealed : IDisposable
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

