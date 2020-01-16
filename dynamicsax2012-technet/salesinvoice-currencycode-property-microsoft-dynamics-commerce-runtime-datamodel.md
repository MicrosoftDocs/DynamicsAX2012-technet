---
title: SalesInvoice.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.currencycode(v=AX.60)
ms:contentKeyID: 62214601
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property

Gets or sets the currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CURRENCYCODE")> _
Public Property CurrencyCode As String
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As String

value = instance.CurrencyCode

instance.CurrencyCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CURRENCYCODE")]
public string CurrencyCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CURRENCYCODE")]
public:
property String^ CurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The currency code.  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

