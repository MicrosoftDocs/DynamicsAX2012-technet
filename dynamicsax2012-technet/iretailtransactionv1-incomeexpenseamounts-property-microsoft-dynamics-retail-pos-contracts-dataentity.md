---
title: IRetailTransactionV1.IncomeExpenseAmounts Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IncomeExpenseAmounts Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.IncomeExpenseAmounts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.incomeexpenseamounts(v=AX.60)
ms:contentKeyID: 49846063
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.IncomeExpenseAmounts
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseAmounts Property

The total amount of income and expense accounts in the transaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IncomeExpenseAmounts As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.IncomeExpenseAmounts

instance.IncomeExpenseAmounts = value
```

``` csharp
decimal IncomeExpenseAmounts { get; set; }
```

``` c++
property Decimal IncomeExpenseAmounts {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

