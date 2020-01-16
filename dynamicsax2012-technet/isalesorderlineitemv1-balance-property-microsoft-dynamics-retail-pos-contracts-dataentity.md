---
title: ISalesOrderLineItemV1.Balance Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderLineItemV1.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalesorderlineitemv1.balance(v=AX.60)
ms:contentKeyID: 49827766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderLineItemV1.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property

The balance of the sales order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Balance As Decimal
    Get
    Set
'Usage
Dim instance As ISalesOrderLineItemV1
Dim value As Decimal

value = instance.Balance

instance.Balance = value
```

``` csharp
decimal Balance { get; set; }
```

``` c++
property Decimal Balance {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ISalesOrderLineItemV1 Interface](isalesorderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

