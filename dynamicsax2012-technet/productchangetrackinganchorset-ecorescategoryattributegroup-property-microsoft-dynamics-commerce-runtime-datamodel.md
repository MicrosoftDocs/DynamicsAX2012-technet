---
title: ProductChangeTrackingAnchorSet.EcoResCategoryAttributeGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResCategoryAttributeGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResCategoryAttributeGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecorescategoryattributegroup(v=AX.60)
ms:contentKeyID: 62213508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResCategoryAttributeGroup
dev_langs:
- CSharp
- C++
- VB
---

# EcoResCategoryAttributeGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESCATEGORYATTRIBUTEGROUP")> _
Public Property EcoResCategoryAttributeGroup As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResCategoryAttributeGroup

instance.EcoResCategoryAttributeGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESCATEGORYATTRIBUTEGROUP")]
public long EcoResCategoryAttributeGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESCATEGORYATTRIBUTEGROUP")]
public:
property long long EcoResCategoryAttributeGroup {
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

