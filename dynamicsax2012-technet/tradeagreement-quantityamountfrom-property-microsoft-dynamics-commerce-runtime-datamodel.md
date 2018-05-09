---
title: TradeAgreement.QuantityAmountFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityAmountFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.QuantityAmountFrom
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.quantityamountfrom(v=AX.60)
ms:contentKeyID: 49833460
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.QuantityAmountFrom
dev_langs:
- CSharp
- C++
- VB
---

# QuantityAmountFrom Property

Gets the minimum quantity required for this rule to apply.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QUANTITYAMOUNTFROM")> _
<DataMemberAttribute> _
Public Property QuantityAmountFrom As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.QuantityAmountFrom
```

``` csharp
[ColumnAttribute("QUANTITYAMOUNTFROM")]
[DataMemberAttribute]
public decimal QuantityAmountFrom { get; internal set; }
```

``` c++
[ColumnAttribute(L"QUANTITYAMOUNTFROM")]
[DataMemberAttribute]
public:
property Decimal QuantityAmountFrom {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

