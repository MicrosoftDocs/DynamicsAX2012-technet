---
title: ProductVariant.ColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ColorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.colorid(v=AX.60)
ms:contentKeyID: 62213928
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ColorId
dev_langs:
- CSharp
- C++
- VB
---

# ColorId Property

Gets the identifer for the color dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COLORID")> _
<DataMemberAttribute> _
Public Property ColorId As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.ColorId

instance.ColorId = value
```

``` csharp
[ColumnAttribute("COLORID")]
[DataMemberAttribute]
public string ColorId { get; set; }
```

``` c++
[ColumnAttribute(L"COLORID")]
[DataMemberAttribute]
public:
property String^ ColorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

