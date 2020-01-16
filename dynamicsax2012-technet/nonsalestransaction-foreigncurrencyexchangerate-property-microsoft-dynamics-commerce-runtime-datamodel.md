---
title: NonSalesTransaction.ForeignCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ForeignCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.ForeignCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.foreigncurrencyexchangerate(v=AX.60)
ms:contentKeyID: 65321127
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.ForeignCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ForeignCurrencyExchangeRate Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXCHRATECUR")> _
<IgnoreDataMemberAttribute> _
Public Property ForeignCurrencyExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As Decimal

value = instance.ForeignCurrencyExchangeRate

instance.ForeignCurrencyExchangeRate = value
```

``` csharp
[ColumnAttribute("EXCHRATECUR")]
[IgnoreDataMemberAttribute]
public decimal ForeignCurrencyExchangeRate { get; set; }
```

``` c++
[ColumnAttribute(L"EXCHRATECUR")]
[IgnoreDataMemberAttribute]
public:
property Decimal ForeignCurrencyExchangeRate {
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

