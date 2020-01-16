---
title: ProductCatalogAssociation.CatalogRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation.CatalogRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalogassociation.catalogrecordid(v=AX.60)
ms:contentKeyID: 62204335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation.CatalogRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogRecordId Property

Gets the associated catalog record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATALOG")> _
<DataMemberAttribute> _
Public Property CatalogRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductCatalogAssociation
Dim value As Long

value = instance.CatalogRecordId
```

``` csharp
[ColumnAttribute("CATALOG")]
[DataMemberAttribute]
public long CatalogRecordId { get; internal set; }
```

``` c++
[ColumnAttribute(L"CATALOG")]
[DataMemberAttribute]
public:
property long long CatalogRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalogAssociation Class](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

