---
title: TenderDetail.ForeignCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ForeignCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.ForeignCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.foreigncurrencyexchangerate(v=AX.60)
ms:contentKeyID: 62209327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.ForeignCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ForeignCurrencyExchangeRate Property

Gets or sets the amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXCHRATE")> _
<DataMemberAttribute> _
Public Property ForeignCurrencyExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As Decimal

value = instance.ForeignCurrencyExchangeRate

instance.ForeignCurrencyExchangeRate = value
```

``` csharp
[ColumnAttribute("EXCHRATE")]
[DataMemberAttribute]
public decimal ForeignCurrencyExchangeRate { get; set; }
```

``` c++
[ColumnAttribute(L"EXCHRATE")]
[DataMemberAttribute]
public:
property Decimal ForeignCurrencyExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The foreign currency exchange rate amount.  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

