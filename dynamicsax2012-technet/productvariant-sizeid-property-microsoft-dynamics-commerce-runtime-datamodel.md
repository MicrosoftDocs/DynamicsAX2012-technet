---
title: ProductVariant.SizeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.SizeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.sizeid(v=AX.60)
ms:contentKeyID: 62211596
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.SizeId
dev_langs:
- CSharp
- C++
- VB
---

# SizeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifer for the size dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SIZEID")> _
<DataMemberAttribute> _
Public Property SizeId As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.SizeId

instance.SizeId = value
```

``` csharp
[ColumnAttribute("SIZEID")]
[DataMemberAttribute]
public string SizeId { get; set; }
```

``` c++
[ColumnAttribute(L"SIZEID")]
[DataMemberAttribute]
public:
property String^ SizeId {
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

