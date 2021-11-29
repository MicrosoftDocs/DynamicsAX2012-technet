---
title: DatabaseContext.BeginTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BeginTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.BeginTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.begintransaction(v=AX.60)
ms:contentKeyID: 65321075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.BeginTransaction
dev_langs:
- CSharp
- C++
- VB
---

# BeginTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Begins a transaction on the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Function BeginTransaction As IDatabaseTransaction
'Usage
Dim instance As DatabaseContext
Dim returnValue As IDatabaseTransaction

returnValue = instance.BeginTransaction()
```

``` csharp
public IDatabaseTransaction BeginTransaction()
```

``` c++
public:
IDatabaseTransaction^ BeginTransaction()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseTransaction](idatabasetransaction-interface-microsoft-dynamics-commerce-runtime-data.md)  
The database transaction.  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

