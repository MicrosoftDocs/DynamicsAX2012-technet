---
title: TenderDetail.CompanyCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.CompanyCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.companycurrencyexchangerate(v=AX.60)
ms:contentKeyID: 65319016
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.CompanyCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrencyExchangeRate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("EXCHRATEMST")> _
Public Property CompanyCurrencyExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As Decimal

value = instance.CompanyCurrencyExchangeRate

instance.CompanyCurrencyExchangeRate = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("EXCHRATEMST")]
public decimal CompanyCurrencyExchangeRate { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"EXCHRATEMST")]
public:
property Decimal CompanyCurrencyExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

