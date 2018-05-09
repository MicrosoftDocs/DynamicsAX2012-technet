---
title: ITransactionSystemV1.LoadTransactionStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: LoadTransactionStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.LoadTransactionStatus(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv1.loadtransactionstatus(v=AX.60)
ms:contentKeyID: 47128484
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.LoadTransactionStatus
dev_langs:
- CSharp
- C++
- VB
---

# LoadTransactionStatus Method

Load the transaction with information received from the terminal, e.g. terminal id, staff id, etc.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub LoadTransactionStatus ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionSystemV1
Dim transaction As IPosTransaction

instance.LoadTransactionStatus(transaction)
```

``` csharp
void LoadTransactionStatus(
    IPosTransaction transaction
)
```

``` c++
void LoadTransactionStatus(
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

