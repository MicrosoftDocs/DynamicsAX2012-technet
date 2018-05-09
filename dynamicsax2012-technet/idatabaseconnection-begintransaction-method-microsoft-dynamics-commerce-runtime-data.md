---
title: IDatabaseConnection.BeginTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BeginTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection.BeginTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.idatabaseconnection.begintransaction(v=AX.60)
ms:contentKeyID: 65315739
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection.BeginTransaction
dev_langs:
- CSharp
- C++
- VB
---

# BeginTransaction Method

Begins a transaction on this connection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function BeginTransaction As IDatabaseTransaction
'Usage
Dim instance As IDatabaseConnection
Dim returnValue As IDatabaseTransaction

returnValue = instance.BeginTransaction()
```

``` csharp
IDatabaseTransaction BeginTransaction()
```

``` c++
IDatabaseTransaction^ BeginTransaction()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseTransaction](idatabasetransaction-interface-microsoft-dynamics-commerce-runtime-data.md)  
The transaction object.  

## See Also

#### Reference

[IDatabaseConnection Interface](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

