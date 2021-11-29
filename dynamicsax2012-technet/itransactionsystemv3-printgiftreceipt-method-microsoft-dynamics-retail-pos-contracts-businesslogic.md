---
title: ITransactionSystemV3.PrintGiftReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: PrintGiftReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV3.PrintGiftReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv3.printgiftreceipt(v=AX.60)
ms:contentKeyID: 62201983
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV3.PrintGiftReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintGiftReceipt Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints gift receipt of a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintGiftReceipt ( _
    transaction As IPosTransaction, _
    copyReceipt As Boolean, _
    printPreview As Boolean _
)
'Usage
Dim instance As ITransactionSystemV3
Dim transaction As IPosTransaction
Dim copyReceipt As Boolean
Dim printPreview As Boolean

instance.PrintGiftReceipt(transaction, _
    copyReceipt, printPreview)
```

``` csharp
void PrintGiftReceipt(
    IPosTransaction transaction,
    bool copyReceipt,
    bool printPreview
)
```

``` c++
void PrintGiftReceipt(
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

[ITransactionSystemV3 Interface](itransactionsystemv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

