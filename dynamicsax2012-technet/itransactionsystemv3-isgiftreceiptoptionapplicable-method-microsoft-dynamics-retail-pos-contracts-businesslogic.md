---
title: ITransactionSystemV3.IsGiftReceiptOptionApplicable Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: IsGiftReceiptOptionApplicable Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV3.IsGiftReceiptOptionApplicable(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv3.isgiftreceiptoptionapplicable(v=AX.60)
ms:contentKeyID: 62204512
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV3.IsGiftReceiptOptionApplicable
dev_langs:
- CSharp
- C++
- VB
---

# IsGiftReceiptOptionApplicable Method

Determines if receipt is applicable for a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsGiftReceiptOptionApplicable ( _
    transaction As IPosTransaction _
) As Boolean
'Usage
Dim instance As ITransactionSystemV3
Dim transaction As IPosTransaction
Dim returnValue As Boolean

returnValue = instance.IsGiftReceiptOptionApplicable(transaction)
```

``` csharp
bool IsGiftReceiptOptionApplicable(
    IPosTransaction transaction
)
```

``` c++
bool IsGiftReceiptOptionApplicable(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if gift receipt is applicable  

## See Also

#### Reference

[ITransactionSystemV3 Interface](itransactionsystemv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

