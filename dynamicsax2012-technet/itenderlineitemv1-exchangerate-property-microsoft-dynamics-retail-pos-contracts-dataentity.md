---
title: ITenderLineItemV1.ExchangeRate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.exchangerate(v=AX.60)
ms:contentKeyID: 49835757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.ExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRate Property

The exchange rate used to calculate the amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
Dim value As Decimal

value = instance.ExchangeRate

instance.ExchangeRate = value
```

``` csharp
decimal ExchangeRate { get; set; }
```

``` c++
property Decimal ExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

