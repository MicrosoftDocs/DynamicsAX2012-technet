---
title: CurrencyAmount.ConvertedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConvertedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.ConvertedAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.currencyamount.convertedamount(v=AX.60)
ms:contentKeyID: 62208079
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.ConvertedAmount
dev_langs:
- CSharp
- C++
- VB
---

# ConvertedAmount Property

Gets or sets the requested amount in foreign currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ConvertedAmount As Decimal
    Get
    Set
'Usage
Dim instance As CurrencyAmount
Dim value As Decimal

value = instance.ConvertedAmount

instance.ConvertedAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal ConvertedAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ConvertedAmount {
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

