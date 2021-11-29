---
title: SalesLine.ProductSource Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSource Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductSource
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.productsource(v=AX.60)
ms:contentKeyID: 62214756
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductSource
dev_langs:
- CSharp
- C++
- VB
---

# ProductSource Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCTSOURCE")> _
<IgnoreDataMemberAttribute> _
Public Property ProductSource As ProductSource
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As ProductSource

value = instance.ProductSource

instance.ProductSource = value
```

``` csharp
[ColumnAttribute("PRODUCTSOURCE")]
[IgnoreDataMemberAttribute]
public ProductSource ProductSource { get; set; }
```

``` c++
[ColumnAttribute(L"PRODUCTSOURCE")]
[IgnoreDataMemberAttribute]
public:
property ProductSource ProductSource {
    ProductSource get ();
    void set (ProductSource value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource](productsource-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductSource](productsource-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

