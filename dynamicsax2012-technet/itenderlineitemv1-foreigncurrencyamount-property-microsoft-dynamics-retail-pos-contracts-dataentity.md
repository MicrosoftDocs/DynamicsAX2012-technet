---
title: ITenderLineItemV1.ForeignCurrencyAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ForeignCurrencyAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ForeignCurrencyAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.foreigncurrencyamount(v=AX.60)
ms:contentKeyID: 49852360
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ForeignCurrencyAmount
dev_langs:
- CSharp
- C++
- VB
---

# ForeignCurrencyAmount Property

The amount in a foreign currency

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ForeignCurrencyAmount As Decimal
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
Dim value As Decimal

value = instance.ForeignCurrencyAmount

instance.ForeignCurrencyAmount = value
```

``` csharp
decimal ForeignCurrencyAmount { get; set; }
```

``` c++
property Decimal ForeignCurrencyAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

