---
title: ProductAttributeSchemaEntry.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.catalogid(v=AX.60)
ms:contentKeyID: 65320688
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

Gets or sets a value indicating whether this is a primary category for the associated product.

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
Dim instance As ProductAttributeSchemaEntry
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

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

