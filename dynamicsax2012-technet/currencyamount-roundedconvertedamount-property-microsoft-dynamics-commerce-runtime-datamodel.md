---
title: CurrencyAmount.RoundedConvertedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundedConvertedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.RoundedConvertedAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currencyamount.roundedconvertedamount(v=AX.60)
ms:contentKeyID: 62201895
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.RoundedConvertedAmount
dev_langs:
- CSharp
- C++
- VB
---

# RoundedConvertedAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the rounded requested amount in foreign currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RoundedConvertedAmount As Decimal
    Get
    Set
'Usage
Dim instance As CurrencyAmount
Dim value As Decimal

value = instance.RoundedConvertedAmount

instance.RoundedConvertedAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal RoundedConvertedAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal RoundedConvertedAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CurrencyAmount Class](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

