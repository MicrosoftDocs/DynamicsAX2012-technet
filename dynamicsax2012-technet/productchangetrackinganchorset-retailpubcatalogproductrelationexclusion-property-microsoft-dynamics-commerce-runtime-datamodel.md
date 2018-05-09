---
title: ProductChangeTrackingAnchorSet.RetailPubCatalogProductRelationExclusion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailPubCatalogProductRelationExclusion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubCatalogProductRelationExclusion
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailpubcatalogproductrelationexclusion(v=AX.60)
ms:contentKeyID: 62212803
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubCatalogProductRelationExclusion
dev_langs:
- CSharp
- C++
- VB
---

# RetailPubCatalogProductRelationExclusion Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILPUBCATALOGPRODUCTRELATIONEXCLUSION")> _
Public Property RetailPubCatalogProductRelationExclusion As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailPubCatalogProductRelationExclusion

instance.RetailPubCatalogProductRelationExclusion = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILPUBCATALOGPRODUCTRELATIONEXCLUSION")]
public long RetailPubCatalogProductRelationExclusion { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILPUBCATALOGPRODUCTRELATIONEXCLUSION")]
public:
property long long RetailPubCatalogProductRelationExclusion {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

