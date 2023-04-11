---
title: TaxCodeInterval.TaxOnTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOnTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxOnTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxontax(v=AX.60)
ms:contentKeyID: 62209223
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxOnTax
dev_langs:
- CSharp
- C++
- VB
---

# TaxOnTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax on tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXONTAX")> _
<DataMemberAttribute> _
Public Property TaxOnTax As String
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As String

value = instance.TaxOnTax
```

``` csharp
[ColumnAttribute("TAXONTAX")]
[DataMemberAttribute]
public string TaxOnTax { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXONTAX")]
[DataMemberAttribute]
public:
property String^ TaxOnTax {
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

