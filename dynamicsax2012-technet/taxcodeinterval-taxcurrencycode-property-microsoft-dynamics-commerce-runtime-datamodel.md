---
title: TaxCodeInterval.TaxCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxcurrencycode(v=AX.60)
ms:contentKeyID: 62214622
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXCURRENCYCODE")> _
Public Property TaxCurrencyCode As String
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As String

value = instance.TaxCurrencyCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXCURRENCYCODE")]
public string TaxCurrencyCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXCURRENCYCODE")]
public:
property String^ TaxCurrencyCode {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

