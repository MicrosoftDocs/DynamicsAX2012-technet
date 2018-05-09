---
title: ProductVariant.Color Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Color Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Color
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.color(v=AX.60)
ms:contentKeyID: 62210636
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Color
dev_langs:
- CSharp
- C++
- VB
---

# Color Property

Gets or sets the value for the color dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COLOR")> _
<DataMemberAttribute> _
Public Property Color As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.Color

instance.Color = value
```

``` csharp
[ColumnAttribute("COLOR")]
[DataMemberAttribute]
public string Color { get; set; }
```

``` c++
[ColumnAttribute(L"COLOR")]
[DataMemberAttribute]
public:
property String^ Color {
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

