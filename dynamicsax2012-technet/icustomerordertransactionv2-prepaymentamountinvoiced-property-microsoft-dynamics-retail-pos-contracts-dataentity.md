---
title: ICustomerOrderTransactionV2.PrepaymentAmountInvoiced Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrepaymentAmountInvoiced Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountInvoiced
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.prepaymentamountinvoiced(v=AX.60)
ms:contentKeyID: 49839152
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountInvoiced
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountInvoiced Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Amount of Prepayment that has been invoiced as part of a Pickup.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrepaymentAmountInvoiced As Decimal
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As Decimal

value = instance.PrepaymentAmountInvoiced

instance.PrepaymentAmountInvoiced = value
```

``` csharp
decimal PrepaymentAmountInvoiced { get; set; }
```

``` c++
property Decimal PrepaymentAmountInvoiced {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

