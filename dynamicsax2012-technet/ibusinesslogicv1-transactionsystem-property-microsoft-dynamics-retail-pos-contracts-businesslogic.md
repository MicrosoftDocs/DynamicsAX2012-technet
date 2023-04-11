---
title: IBusinessLogicV1.TransactionSystem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: TransactionSystem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.TransactionSystem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.ibusinesslogicv1.transactionsystem(v=AX.60)
ms:contentKeyID: 47128247
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.TransactionSystem
dev_langs:
- CSharp
- C++
- VB
---

# TransactionSystem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TransactionSystem As ITransactionSystem
    Get
'Usage
Dim instance As IBusinessLogicV1
Dim value As ITransactionSystem

value = instance.TransactionSystem
```

``` csharp
ITransactionSystem TransactionSystem { get; }
```

``` c++
property ITransactionSystem^ TransactionSystem {
    ITransactionSystem^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystem](itransactionsystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)  
Returns [ITransactionSystem](itransactionsystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md).  

## See Also

#### Reference

[IBusinessLogicV1 Interface](ibusinesslogicv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

