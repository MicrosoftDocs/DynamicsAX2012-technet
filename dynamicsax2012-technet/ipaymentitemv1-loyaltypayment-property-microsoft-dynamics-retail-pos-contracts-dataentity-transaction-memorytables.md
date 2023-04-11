---
title: IPaymentItemV1.LoyaltyPayment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables)
TOCTitle: LoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IPaymentItemV1.LoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.transaction.memorytables.ipaymentitemv1.loyaltypayment(v=AX.60)
ms:contentKeyID: 62201732
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IPaymentItemV1.LoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyPayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines whether it is a loyalty card refund.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As IPaymentItemV1
Dim value As Boolean

value = instance.LoyaltyPayment

instance.LoyaltyPayment = value
```

``` csharp
bool LoyaltyPayment { get; set; }
```

``` c++
property bool LoyaltyPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IPaymentItemV1 Interface](ipaymentitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)

