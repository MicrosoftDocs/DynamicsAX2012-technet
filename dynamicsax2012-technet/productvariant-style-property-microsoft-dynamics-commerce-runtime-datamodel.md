---
title: ProductVariant.Style Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Style Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Style
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.style(v=AX.60)
ms:contentKeyID: 62209557
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Style
dev_langs:
- CSharp
- C++
- VB
---

# Style Property

Gets or sets the value for the style dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STYLE")> _
Public Property Style As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.Style

instance.Style = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STYLE")]
public string Style { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STYLE")]
public:
property String^ Style {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

