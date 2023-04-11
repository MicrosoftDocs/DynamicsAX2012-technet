---
title: ICustomerPaymentTransactionV1.TransSalePmtDiff Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TransSalePmtDiff Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.TransSalePmtDiff
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerpaymenttransactionv1.transsalepmtdiff(v=AX.60)
ms:contentKeyID: 49820780
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.TransSalePmtDiff
dev_langs:
- CSharp
- C++
- VB
---

# TransSalePmtDiff Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the trans sale PMT diff.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TransSalePmtDiff As Decimal
    Get
    Set
'Usage
Dim instance As ICustomerPaymentTransactionV1
Dim value As Decimal

value = instance.TransSalePmtDiff

instance.TransSalePmtDiff = value
```

``` csharp
decimal TransSalePmtDiff { get; set; }
```

``` c++
property Decimal TransSalePmtDiff {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerPaymentTransactionV1 Interface](icustomerpaymenttransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

