---
title: ICustomerOrderTransactionV2.PrepaymentAmountRequired Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrepaymentAmountRequired Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.prepaymentamountrequired(v=AX.60)
ms:contentKeyID: 49837084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountRequired
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountRequired Property

Amount of Prepayment required for this order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrepaymentAmountRequired As Decimal
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As Decimal

value = instance.PrepaymentAmountRequired

instance.PrepaymentAmountRequired = value
```

``` csharp
decimal PrepaymentAmountRequired { get; set; }
```

``` c++
property Decimal PrepaymentAmountRequired {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This is NOT a running total, to determine the current amount due, compare (PrepaymentAmountRequired - PrepaymentAmoundPaid)

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

