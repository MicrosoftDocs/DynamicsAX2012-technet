---
title: ProductExistenceCriteria.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria.CatalogId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productexistencecriteria.catalogid(v=AX.60)
ms:contentKeyID: 62205165
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

Gets or sets a catalog Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As ProductExistenceCriteria
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[DataMemberAttribute]
public long CatalogId { get; set; }
```

``` c++
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

[ProductExistenceCriteria Class](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

