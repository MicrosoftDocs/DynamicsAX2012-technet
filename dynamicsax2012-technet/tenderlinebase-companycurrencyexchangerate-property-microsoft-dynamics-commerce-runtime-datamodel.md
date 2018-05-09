---
title: TenderLineBase.CompanyCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CompanyCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.companycurrencyexchangerate(v=AX.60)
ms:contentKeyID: 62213823
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CompanyCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrencyExchangeRate Property

Gets or sets the company specific currency exchange rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMPANYCURRENCYEXCHANGERATE")> _
<DataMemberAttribute> _
Public Property CompanyCurrencyExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Decimal

value = instance.CompanyCurrencyExchangeRate

instance.CompanyCurrencyExchangeRate = value
```

``` csharp
[ColumnAttribute("COMPANYCURRENCYEXCHANGERATE")]
[DataMemberAttribute]
public decimal CompanyCurrencyExchangeRate { get; set; }
```

``` c++
[ColumnAttribute(L"COMPANYCURRENCYEXCHANGERATE")]
[DataMemberAttribute]
public:
property Decimal CompanyCurrencyExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The currency.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

