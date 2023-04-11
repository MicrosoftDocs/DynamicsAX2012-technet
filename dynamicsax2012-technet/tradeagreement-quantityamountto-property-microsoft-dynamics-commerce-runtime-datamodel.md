---
title: TradeAgreement.QuantityAmountTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityAmountTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.QuantityAmountTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.quantityamountto(v=AX.60)
ms:contentKeyID: 49820753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.QuantityAmountTo
dev_langs:
- CSharp
- C++
- VB
---

# QuantityAmountTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum quantity allowed for this rule to apply.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUANTITYAMOUNTTO")> _
Public Property QuantityAmountTo As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.QuantityAmountTo
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUANTITYAMOUNTTO")]
public decimal QuantityAmountTo { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUANTITYAMOUNTTO")]
public:
property Decimal QuantityAmountTo {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

