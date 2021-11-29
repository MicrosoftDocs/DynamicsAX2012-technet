---
title: IDatabaseConnection.Open Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Open Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection.Open
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseconnection.open(v=AX.60)
ms:contentKeyID: 65319861
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection.Open
dev_langs:
- CSharp
- C++
- VB
---

# Open Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Opens the connection on the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub Open
'Usage
Dim instance As IDatabaseConnection

instance.Open()
```

``` csharp
void Open()
```

``` c++
void Open()
```

## Remarks

This operation must be performed on the connection before any other action can be executed using the connection.

The connection should be disposed calling [Dispose()](https://technet.microsoft.com/library/es4s3w1d\(v=ax.60\)) on this object.

## See Also

#### Reference

[IDatabaseConnection Interface](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

