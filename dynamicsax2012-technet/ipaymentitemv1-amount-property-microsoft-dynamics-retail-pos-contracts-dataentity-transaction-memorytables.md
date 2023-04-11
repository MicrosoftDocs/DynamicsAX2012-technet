---
title: IPaymentItemV1.Amount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IPaymentItemV1.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.transaction.memorytables.ipaymentitemv1.amount(v=AX.60)
ms:contentKeyID: 62204368
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IPaymentItemV1.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Payment amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As IPaymentItemV1
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
decimal Amount { get; set; }
```

``` c++
property Decimal Amount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IPaymentItemV1 Interface](ipaymentitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)

