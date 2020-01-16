---
title: ProductVariant.Size Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Size Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Size
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.size(v=AX.60)
ms:contentKeyID: 62207297
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Size
dev_langs:
- CSharp
- C++
- VB
---

# Size Property

Gets or sets the value for the size dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SIZE")> _
Public Property Size As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.Size

instance.Size = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SIZE")]
public string Size { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SIZE")]
public:
property String^ Size {
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

