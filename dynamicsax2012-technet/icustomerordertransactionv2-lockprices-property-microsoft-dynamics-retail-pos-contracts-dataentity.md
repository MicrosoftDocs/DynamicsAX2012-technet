---
title: ICustomerOrderTransactionV2.LockPrices Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LockPrices Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.LockPrices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.lockprices(v=AX.60)
ms:contentKeyID: 49821293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.LockPrices
dev_langs:
- CSharp
- C++
- VB
---

# LockPrices Property

Set whether or not prices are fixed, and not automatically calculated/updated/refreshed

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LockPrices As Boolean
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As Boolean

value = instance.LockPrices

instance.LockPrices = value
```

``` csharp
bool LockPrices { get; set; }
```

``` c++
property bool LockPrices {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

