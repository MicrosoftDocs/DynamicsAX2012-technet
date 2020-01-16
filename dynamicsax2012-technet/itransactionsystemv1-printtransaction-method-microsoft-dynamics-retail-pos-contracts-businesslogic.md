---
title: ITransactionSystemV1.PrintTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: PrintTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.PrintTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv1.printtransaction(v=AX.60)
ms:contentKeyID: 47128236
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.PrintTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PrintTransaction Method

Prints the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintTransaction ( _
    transaction As IPosTransaction, _
    copyReceipt As Boolean, _
    printPreview As Boolean _
)
'Usage
Dim instance As ITransactionSystemV1
Dim transaction As IPosTransaction
Dim copyReceipt As Boolean
Dim printPreview As Boolean

instance.PrintTransaction(transaction, _
    copyReceipt, printPreview)
```

``` csharp
void PrintTransaction(
    IPosTransaction transaction,
    bool copyReceipt,
    bool printPreview
)
```

``` c++
void PrintTransaction(
    IPosTransaction^ transaction, 
    bool copyReceipt, 
    bool printPreview
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - printPreview  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ITransactionSystemV1 Interface](itransactionsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

