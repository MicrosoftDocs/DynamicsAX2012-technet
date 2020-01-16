---
title: ProductVariant.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.VariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.variantid(v=AX.60)
ms:contentKeyID: 62201798
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property

Gets or sets the string-based retail variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VARIANTID")> _
<DataMemberAttribute> _
Public Property VariantId As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.VariantId

instance.VariantId = value
```

``` csharp
[ColumnAttribute("VARIANTID")]
[DataMemberAttribute]
public string VariantId { get; set; }
```

``` c++
[ColumnAttribute(L"VARIANTID")]
[DataMemberAttribute]
public:
property String^ VariantId {
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

