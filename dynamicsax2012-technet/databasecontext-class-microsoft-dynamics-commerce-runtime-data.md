---
title: DatabaseContext Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseContext Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext(v=AX.60)
ms:contentKeyID: 65318519
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseContext Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Wraps common operations associated to database access, maintaining single database connection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DatabaseContext _
    Implements IDisposable
'Usage
Dim instance As DatabaseContext
```

``` csharp
public abstract class DatabaseContext : IDisposable
```

``` c++
public ref class DatabaseContext abstract : IDisposable
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

