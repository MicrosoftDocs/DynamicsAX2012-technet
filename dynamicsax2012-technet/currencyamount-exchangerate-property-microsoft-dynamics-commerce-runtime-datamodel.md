---
title: CurrencyAmount.ExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.ExchangeRate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.currencyamount.exchangerate(v=AX.60)
ms:contentKeyID: 62207896
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.ExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRate Property

Gets or sets the exchange rate of the converted amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As CurrencyAmount
Dim value As Decimal

value = instance.ExchangeRate

instance.ExchangeRate = value
```

``` csharp
[DataMemberAttribute]
public decimal ExchangeRate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CurrencyAmount Class](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

