---
title: ICustomerPaymentTransactionV1.NoOfDeposits Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NoOfDeposits Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.NoOfDeposits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerpaymenttransactionv1.noofdeposits(v=AX.60)
ms:contentKeyID: 49832769
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.NoOfDeposits
dev_langs:
- CSharp
- C++
- VB
---

# NoOfDeposits Property

Gets or sets the no of deposits.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property NoOfDeposits As Integer
    Get
    Set
'Usage
Dim instance As ICustomerPaymentTransactionV1
Dim value As Integer

value = instance.NoOfDeposits

instance.NoOfDeposits = value
```

``` csharp
int NoOfDeposits { get; set; }
```

``` c++
property int NoOfDeposits {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerPaymentTransactionV1 Interface](icustomerpaymenttransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

