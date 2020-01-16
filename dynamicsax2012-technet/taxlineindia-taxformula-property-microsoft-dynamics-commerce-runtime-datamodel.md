---
title: TaxLineIndia.TaxFormula Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxFormula Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxFormula
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxformula(v=AX.60)
ms:contentKeyID: 62211911
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxFormula
dev_langs:
- CSharp
- C++
- VB
---

# TaxFormula Property

Gets or sets tax formula as a string.

For example, if the formula of a tax item is +\[ST-DL\]+\[ST-KA\], the property will be valued as "ST-DL, ST-KA".

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXFORMULA")> _
Public Property TaxFormula As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.TaxFormula

instance.TaxFormula = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXFORMULA")]
public string TaxFormula { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXFORMULA")]
public:
property String^ TaxFormula {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

