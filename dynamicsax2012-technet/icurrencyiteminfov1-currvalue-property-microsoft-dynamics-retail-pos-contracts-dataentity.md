---
title: ICurrencyItemInfoV1.CurrValue Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CurrValue Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfoV1.CurrValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icurrencyiteminfov1.currvalue(v=AX.60)
ms:contentKeyID: 47128289
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfoV1.CurrValue
dev_langs:
- CSharp
- C++
- VB
---

# CurrValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The value of a currency item. For example, a 10 dollar bill.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CurrValue As Decimal
    Get
    Set
'Usage
Dim instance As ICurrencyItemInfoV1
Dim value As Decimal

value = instance.CurrValue

instance.CurrValue = value
```

``` csharp
decimal CurrValue { get; set; }
```

``` c++
property Decimal CurrValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ICurrencyItemInfoV1 Interface](icurrencyiteminfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

