---
title: ITransactionTriggerV1.SaveTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: SaveTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.SaveTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Data.SqlClient.SqlTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1.savetransaction(v=AX.60)
ms:contentKeyID: 47128575
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.SaveTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SaveTransaction Method

Called when a transaction is saved to the database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SaveTransaction ( _
    posTransaction As IPosTransaction, _
    sqlTransaction As SqlTransaction _
)
'Usage
Dim instance As ITransactionTriggerV1
Dim posTransaction As IPosTransaction
Dim sqlTransaction As SqlTransaction

instance.SaveTransaction(posTransaction, _
    sqlTransaction)
```

``` csharp
void SaveTransaction(
    IPosTransaction posTransaction,
    SqlTransaction sqlTransaction
)
```

``` c++
void SaveTransaction(
    IPosTransaction^ posTransaction, 
    SqlTransaction^ sqlTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - sqlTransaction  
    Type: [System.Data.SqlClient.SqlTransaction](https://technet.microsoft.com/en-us/library/4b1h6b1d\(v=ax.60\))  

## Remarks

Use the provided sqlTransaction object to write to the database. Do not commit or roll back the transaction, or close the connection.

Any exception that results from this trigger will roll back the saving process for a POS transaction to the database.

## See Also

#### Reference

[ITransactionTriggerV1 Interface](itransactiontriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

