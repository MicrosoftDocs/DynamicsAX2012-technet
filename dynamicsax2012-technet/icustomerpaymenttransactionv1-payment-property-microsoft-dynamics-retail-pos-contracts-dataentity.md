---
title: ICustomerPaymentTransactionV1.Payment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Payment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.Payment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerpaymenttransactionv1.payment(v=AX.60)
ms:contentKeyID: 49854449
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.Payment
dev_langs:
- CSharp
- C++
- VB
---

# Payment Property

Gets or sets the payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Payment As Decimal
    Get
    Set
'Usage
Dim instance As ICustomerPaymentTransactionV1
Dim value As Decimal

value = instance.Payment

instance.Payment = value
```

``` csharp
decimal Payment { get; set; }
```

``` c++
property Decimal Payment {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerPaymentTransactionV1 Interface](icustomerpaymenttransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

