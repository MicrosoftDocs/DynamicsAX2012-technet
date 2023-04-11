---
title: ISuspendRetrieveSystemV1.SuspendTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SuspendTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.SuspendTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.isuspendretrievesystemv1.suspendtransaction(v=AX.60)
ms:contentKeyID: 62204274
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.SuspendTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SuspendTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Suspendes a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SuspendTransaction ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ISuspendRetrieveSystemV1
Dim transaction As IPosTransaction

instance.SuspendTransaction(transaction)
```

``` csharp
void SuspendTransaction(
    IPosTransaction transaction
)
```

``` c++
void SuspendTransaction(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISuspendRetrieveSystemV1 Interface](isuspendretrievesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

