---
title: Currency.RoundOffPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundOffPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currency.roundoffprice(v=AX.60)
ms:contentKeyID: 62214770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffPrice
dev_langs:
- CSharp
- C++
- VB
---

# RoundOffPrice Property

Gets or sets the round off price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ROUNDOFFPRICE")> _
Public Property RoundOffPrice As Decimal
    Get
    Set
'Usage
Dim instance As Currency
Dim value As Decimal

value = instance.RoundOffPrice

instance.RoundOffPrice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ROUNDOFFPRICE")]
public decimal RoundOffPrice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ROUNDOFFPRICE")]
public:
property Decimal RoundOffPrice {
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

