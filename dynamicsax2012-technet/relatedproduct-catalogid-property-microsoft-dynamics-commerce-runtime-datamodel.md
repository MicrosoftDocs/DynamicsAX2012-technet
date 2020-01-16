---
title: RelatedProduct.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.catalogid(v=AX.60)
ms:contentKeyID: 62206898
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

Gets or sets the catalog id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATALOG")> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATALOG")]
public long CatalogId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATALOG")]
public:
property long long CatalogId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RelatedProduct Class](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

