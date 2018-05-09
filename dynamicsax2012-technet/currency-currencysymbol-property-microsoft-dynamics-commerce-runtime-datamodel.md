---
title: Currency.CurrencySymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencySymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.CurrencySymbol
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.currency.currencysymbol(v=AX.60)
ms:contentKeyID: 62206631
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.CurrencySymbol
dev_langs:
- CSharp
- C++
- VB
---

# CurrencySymbol Property

Gets or sets the currency symbol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SYMBOL")> _
Public Property CurrencySymbol As String
    Get
    Set
'Usage
Dim instance As Currency
Dim value As String

value = instance.CurrencySymbol

instance.CurrencySymbol = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SYMBOL")]
public string CurrencySymbol { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SYMBOL")]
public:
property String^ CurrencySymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Currency Class](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

