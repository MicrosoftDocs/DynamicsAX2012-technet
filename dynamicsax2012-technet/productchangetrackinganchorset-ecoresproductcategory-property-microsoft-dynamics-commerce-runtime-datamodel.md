---
title: ProductChangeTrackingAnchorSet.EcoResProductCategory Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResProductCategory Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductCategory
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresproductcategory(v=AX.60)
ms:contentKeyID: 62203934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductCategory
dev_langs:
- CSharp
- C++
- VB
---

# EcoResProductCategory Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESPRODUCTCATEGORY")> _
<DataMemberAttribute> _
Public Property EcoResProductCategory As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResProductCategory

instance.EcoResProductCategory = value
```

``` csharp
[ColumnAttribute("ECORESPRODUCTCATEGORY")]
[DataMemberAttribute]
public long EcoResProductCategory { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESPRODUCTCATEGORY")]
[DataMemberAttribute]
public:
property long long EcoResProductCategory {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

