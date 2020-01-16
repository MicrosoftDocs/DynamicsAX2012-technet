---
title: TenderLineBase.ExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.ExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.exchangerate(v=AX.60)
ms:contentKeyID: 62214035
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.ExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRate Property

Gets or sets the currency exchange rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXCHANGERATE")> _
<DataMemberAttribute> _
Public Property ExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Decimal

value = instance.ExchangeRate

instance.ExchangeRate = value
```

``` csharp
[ColumnAttribute("EXCHANGERATE")]
[DataMemberAttribute]
public decimal ExchangeRate { get; set; }
```

``` c++
[ColumnAttribute(L"EXCHANGERATE")]
[DataMemberAttribute]
public:
property Decimal ExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The currency.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

