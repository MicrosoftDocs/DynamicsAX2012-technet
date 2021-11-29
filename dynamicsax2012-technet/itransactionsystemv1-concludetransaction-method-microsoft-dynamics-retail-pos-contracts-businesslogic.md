---
title: ITransactionSystemV1.ConcludeTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ConcludeTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.ConcludeTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv1.concludetransaction(v=AX.60)
ms:contentKeyID: 47128088
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.ConcludeTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ConcludeTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Does what needs to be done when the transaction is concluded. Updates loyalty, giftcards. Prints transactions; Saves transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ConcludeTransaction ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionSystemV1
Dim transaction As IPosTransaction

instance.ConcludeTransaction(transaction)
```

``` csharp
void ConcludeTransaction(
    IPosTransaction transaction
)
```

``` c++
void ConcludeTransaction(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionSystemV1 Interface](itransactionsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

