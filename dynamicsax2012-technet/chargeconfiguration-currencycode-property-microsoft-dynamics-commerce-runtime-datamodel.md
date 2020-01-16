---
title: ChargeConfiguration.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.currencycode(v=AX.60)
ms:contentKeyID: 49852412
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property

Gets or sets the currency of the configuration rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCYCODE")> _
<DataMemberAttribute> _
Public Property CurrencyCode As String
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As String

value = instance.CurrencyCode

instance.CurrencyCode = value
```

``` csharp
[ColumnAttribute("CURRENCYCODE")]
[DataMemberAttribute]
public string CurrencyCode { get; set; }
```

``` c++
[ColumnAttribute(L"CURRENCYCODE")]
[DataMemberAttribute]
public:
property String^ CurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Used to interpret Value field when it is a Fixed or Pieces charge.

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

