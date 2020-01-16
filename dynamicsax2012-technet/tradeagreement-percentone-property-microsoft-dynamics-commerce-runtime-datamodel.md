---
title: TradeAgreement.PercentOne Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PercentOne Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PercentOne
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.percentone(v=AX.60)
ms:contentKeyID: 49844925
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PercentOne
dev_langs:
- CSharp
- C++
- VB
---

# PercentOne Property

Gets the first percentage from this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PERCENT1")> _
<DataMemberAttribute> _
Public Property PercentOne As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.PercentOne
```

``` csharp
[ColumnAttribute("PERCENT1")]
[DataMemberAttribute]
public decimal PercentOne { get; internal set; }
```

``` c++
[ColumnAttribute(L"PERCENT1")]
[DataMemberAttribute]
public:
property Decimal PercentOne {
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

