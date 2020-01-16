---
title: IRetailTransactionV4.LoyaltyManualDiscountAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyManualDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV4.LoyaltyManualDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv4.loyaltymanualdiscountamount(v=AX.60)
ms:contentKeyID: 62204510
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV4.LoyaltyManualDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyManualDiscountAmount Property

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyManualDiscountAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As IRetailTransactionV4
Dim value As Nullable(Of Decimal)

value = instance.LoyaltyManualDiscountAmount

instance.LoyaltyManualDiscountAmount = value
```

``` csharp
Nullable<decimal> LoyaltyManualDiscountAmount { get; set; }
```

``` c++
property Nullable<Decimal> LoyaltyManualDiscountAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV4 Interface](iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

