---
title: TaxComponentIndia.TaxType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcomponentindia.taxtype(v=AX.60)
ms:contentKeyID: 62208182
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxType
dev_langs:
- CSharp
- C++
- VB
---

# TaxType Property

Gets or sets the tax type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXTYPE")> _
<DataMemberAttribute> _
Public Property TaxType As String
    Get
    Set
'Usage
Dim instance As TaxComponentIndia
Dim value As String

value = instance.TaxType

instance.TaxType = value
```

``` csharp
[ColumnAttribute("TAXTYPE")]
[DataMemberAttribute]
public string TaxType { get; set; }
```

``` c++
[ColumnAttribute(L"TAXTYPE")]
[DataMemberAttribute]
public:
property String^ TaxType {
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

