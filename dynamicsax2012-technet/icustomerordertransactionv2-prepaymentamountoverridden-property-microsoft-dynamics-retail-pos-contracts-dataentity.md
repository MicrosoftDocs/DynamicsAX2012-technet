---
title: ICustomerOrderTransactionV2.PrepaymentAmountOverridden Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrepaymentAmountOverridden Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountOverridden
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.prepaymentamountoverridden(v=AX.60)
ms:contentKeyID: 49831423
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.PrepaymentAmountOverridden
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountOverridden Property

Set true, if pre payment (deposit) amount is overridden.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrepaymentAmountOverridden As Boolean
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As Boolean

value = instance.PrepaymentAmountOverridden

instance.PrepaymentAmountOverridden = value
```

``` csharp
bool PrepaymentAmountOverridden { get; set; }
```

``` c++
property bool PrepaymentAmountOverridden {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

