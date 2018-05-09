---
title: ICardInfoV1.CashBackLimit Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CashBackLimit Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CashBackLimit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.cashbacklimit(v=AX.60)
ms:contentKeyID: 47129013
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CashBackLimit
dev_langs:
- CSharp
- C++
- VB
---

# CashBackLimit Property

Get or set the cash back limit for a debit card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CashBackLimit As Decimal
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As Decimal

value = instance.CashBackLimit

instance.CashBackLimit = value
```

``` csharp
decimal CashBackLimit { get; set; }
```

``` c++
property Decimal CashBackLimit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

