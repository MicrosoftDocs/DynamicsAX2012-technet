---
title: Currency.RoundOffSales Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundOffSales Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffSales
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currency.roundoffsales(v=AX.60)
ms:contentKeyID: 62203442
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffSales
dev_langs:
- CSharp
- C++
- VB
---

# RoundOffSales Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the round off sales.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ROUNDOFFSALES")> _
Public Property RoundOffSales As Decimal
    Get
    Set
'Usage
Dim instance As Currency
Dim value As Decimal

value = instance.RoundOffSales

instance.RoundOffSales = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ROUNDOFFSALES")]
public decimal RoundOffSales { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ROUNDOFFSALES")]
public:
property Decimal RoundOffSales {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Currency Class](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

