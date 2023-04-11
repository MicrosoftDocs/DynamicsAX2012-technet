---
title: ProductCategoryAssociation.CatalogRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.CatalogRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcategoryassociation.catalogrecordid(v=AX.60)
ms:contentKeyID: 62204552
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.CatalogRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the associated catalog record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATALOG")> _
Public Property CatalogRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductCategoryAssociation
Dim value As Long

value = instance.CatalogRecordId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATALOG")]
public long CatalogRecordId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATALOG")]
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

[ProductCategoryAssociation Class](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

