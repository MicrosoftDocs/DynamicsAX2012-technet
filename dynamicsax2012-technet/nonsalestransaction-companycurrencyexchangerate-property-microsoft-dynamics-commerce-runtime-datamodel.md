---
title: NonSalesTransaction.CompanyCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.CompanyCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.companycurrencyexchangerate(v=AX.60)
ms:contentKeyID: 65318042
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.CompanyCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrencyExchangeRate Property

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
Dim instance As NonSalesTransaction
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

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

