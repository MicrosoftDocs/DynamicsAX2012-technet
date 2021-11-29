---
title: ExchangeRate.Rate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Rate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.Rate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.exchangerate.rate(v=AX.60)
ms:contentKeyID: 49847826
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.Rate
dev_langs:
- CSharp
- C++
- VB
---

# Rate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the exchange rate factor from FromCurrency to ToCurrency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXCHANGERATE")> _
Public Property Rate As Decimal
    Get
    Friend Set
'Usage
Dim instance As ExchangeRate
Dim value As Decimal

value = instance.Rate
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXCHANGERATE")]
public decimal Rate { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXCHANGERATE")]
public:
property Decimal Rate {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ExchangeRate Class](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

