---
title: TaxComponentIndia.TaxCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcomponentindia.taxcode(v=AX.60)
ms:contentKeyID: 62213511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXCODE")> _
Public Property TaxCode As String
    Get
    Set
'Usage
Dim instance As TaxComponentIndia
Dim value As String

value = instance.TaxCode

instance.TaxCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXCODE")]
public string TaxCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXCODE")]
public:
property String^ TaxCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxComponentIndia Class](taxcomponentindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

