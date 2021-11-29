---
title: TradeAgreement.PercentTwo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PercentTwo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PercentTwo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.percenttwo(v=AX.60)
ms:contentKeyID: 49838589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.PercentTwo
dev_langs:
- CSharp
- C++
- VB
---

# PercentTwo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the second percentage from this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PERCENT2")> _
Public Property PercentTwo As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.PercentTwo
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERCENT2")]
public decimal PercentTwo { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERCENT2")]
public:
property Decimal PercentTwo {
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

