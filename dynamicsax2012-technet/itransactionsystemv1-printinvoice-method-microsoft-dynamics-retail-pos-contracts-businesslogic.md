---
title: ITransactionSystemV1.PrintInvoice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: PrintInvoice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.PrintInvoice(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv1.printinvoice(v=AX.60)
ms:contentKeyID: 47128117
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV1.PrintInvoice
dev_langs:
- CSharp
- C++
- VB
---

# PrintInvoice Method

Prints the invoice.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintInvoice ( _
    transaction As IPosTransaction, _
    copyInvoice As Boolean, _
    printPreview As Boolean _
)
'Usage
Dim instance As ITransactionSystemV1
Dim transaction As IPosTransaction
Dim copyInvoice As Boolean
Dim printPreview As Boolean

instance.PrintInvoice(transaction, copyInvoice, _
    printPreview)
```

``` csharp
void PrintInvoice(
    IPosTransaction transaction,
    bool copyInvoice,
    bool printPreview
)
```

``` c++
void PrintInvoice(
    IPosTransaction^ transaction, 
    bool copyInvoice, 
    bool printPreview
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyInvoice  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - printPreview  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ITransactionSystemV1 Interface](itransactionsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

