---
title: ExchangeRate.ToCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.ToCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.exchangerate.tocurrency(v=AX.60)
ms:contentKeyID: 49831794
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.ToCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ToCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the target currency for the exchange rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOCURRENCYCODE")> _
<DataMemberAttribute> _
Public Property ToCurrency As String
    Get
    Friend Set
'Usage
Dim instance As ExchangeRate
Dim value As String

value = instance.ToCurrency
```

``` csharp
[ColumnAttribute("TOCURRENCYCODE")]
[DataMemberAttribute]
public string ToCurrency { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOCURRENCYCODE")]
[DataMemberAttribute]
public:
property String^ ToCurrency {
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

