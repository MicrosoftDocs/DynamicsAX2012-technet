---
title: IRetailTransactionV1.NetAmountWithNoTax Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NetAmountWithNoTax Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NetAmountWithNoTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.netamountwithnotax(v=AX.60)
ms:contentKeyID: 49830268
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NetAmountWithNoTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithNoTax Property

The total net amount(grossamount minus discounts) exluding tax.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property NetAmountWithNoTax As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.NetAmountWithNoTax

instance.NetAmountWithNoTax = value
```

``` csharp
decimal NetAmountWithNoTax { get; set; }
```

``` c++
property Decimal NetAmountWithNoTax {
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

