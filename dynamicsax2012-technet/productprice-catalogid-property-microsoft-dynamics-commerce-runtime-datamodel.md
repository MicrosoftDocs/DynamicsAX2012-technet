---
title: ProductPrice.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.CatalogId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.catalogid(v=AX.60)
ms:contentKeyID: 62202096
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

Gets or sets the catalog corresponding to this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATALOG")> _
<DataMemberAttribute> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[ColumnAttribute("CATALOG")]
[DataMemberAttribute]
public long CatalogId { get; set; }
```

``` c++
[ColumnAttribute(L"CATALOG")]
[DataMemberAttribute]
public:
property long long CatalogId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

