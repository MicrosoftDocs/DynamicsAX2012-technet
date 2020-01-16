---
title: TradeAgreement.MarkupAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MarkupAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.MarkupAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.markupamount(v=AX.60)
ms:contentKeyID: 49846393
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.MarkupAmount
dev_langs:
- CSharp
- C++
- VB
---

# MarkupAmount Property

Gets the markup amount to apply when using this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MARKUP")> _
Public Property MarkupAmount As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.MarkupAmount
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MARKUP")]
public decimal MarkupAmount { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MARKUP")]
public:
property Decimal MarkupAmount {
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

