---
title: CurrencyRequest.AmountToConvert Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountToConvert Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyRequest.AmountToConvert
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.currencyrequest.amounttoconvert(v=AX.60)
ms:contentKeyID: 62212484
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyRequest.AmountToConvert
dev_langs:
- CSharp
- C++
- VB
---

# AmountToConvert Property

Gets or sets the amount to be converted by the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AmountToConvert As Decimal
    Get
    Set
'Usage
Dim instance As CurrencyRequest
Dim value As Decimal

value = instance.AmountToConvert

instance.AmountToConvert = value
```

``` csharp
[DataMemberAttribute]
public decimal AmountToConvert { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AmountToConvert {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CurrencyRequest Class](currencyrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

