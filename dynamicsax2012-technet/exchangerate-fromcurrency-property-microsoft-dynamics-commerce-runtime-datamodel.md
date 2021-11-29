---
title: ExchangeRate.FromCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.FromCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.exchangerate.fromcurrency(v=AX.60)
ms:contentKeyID: 49842414
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.FromCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FromCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the source currency for the exchange rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FROMCURRENCYCODE")> _
Public Property FromCurrency As String
    Get
    Friend Set
'Usage
Dim instance As ExchangeRate
Dim value As String

value = instance.FromCurrency
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FROMCURRENCYCODE")]
public string FromCurrency { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FROMCURRENCYCODE")]
public:
property String^ FromCurrency {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ExchangeRate Class](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

