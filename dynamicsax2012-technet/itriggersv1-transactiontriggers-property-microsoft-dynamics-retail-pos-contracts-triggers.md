---
title: ITriggersV1.TransactionTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: TransactionTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.TransactionTriggers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.transactiontriggers(v=AX.60)
ms:contentKeyID: 47129022
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.TransactionTriggers
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTriggers Property

Gets the transaction triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TransactionTriggers As IEnumerable(Of ITransactionTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of ITransactionTrigger)

value = instance.TransactionTriggers
```

``` csharp
IEnumerable<ITransactionTrigger> TransactionTriggers { get; }
```

``` c++
property IEnumerable<ITransactionTrigger^>^ TransactionTriggers {
    IEnumerable<ITransactionTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ITransactionTrigger](itransactiontrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

