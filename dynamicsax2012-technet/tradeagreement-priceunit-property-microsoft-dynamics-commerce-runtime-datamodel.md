---
title: TradeAgreement.PriceUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PriceUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.priceunit(v=AX.60)
ms:contentKeyID: 49841431
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PriceUnit
dev_langs:
- CSharp
- C++
- VB
---

# PriceUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the pricing unit used to interpret amounts and markups on this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEUNIT")> _
<DataMemberAttribute> _
Public Property PriceUnit As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.PriceUnit
```

``` csharp
[ColumnAttribute("PRICEUNIT")]
[DataMemberAttribute]
public decimal PriceUnit { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICEUNIT")]
[DataMemberAttribute]
public:
property Decimal PriceUnit {
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

