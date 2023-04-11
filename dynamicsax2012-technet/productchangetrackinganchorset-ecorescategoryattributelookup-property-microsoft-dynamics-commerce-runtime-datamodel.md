---
title: ProductChangeTrackingAnchorSet.EcoResCategoryAttributeLookup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResCategoryAttributeLookup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResCategoryAttributeLookup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecorescategoryattributelookup(v=AX.60)
ms:contentKeyID: 62204550
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResCategoryAttributeLookup
dev_langs:
- CSharp
- C++
- VB
---

# EcoResCategoryAttributeLookup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESCATEGORYATTRIBUTELOOKUP")> _
<DataMemberAttribute> _
Public Property EcoResCategoryAttributeLookup As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResCategoryAttributeLookup

instance.EcoResCategoryAttributeLookup = value
```

``` csharp
[ColumnAttribute("ECORESCATEGORYATTRIBUTELOOKUP")]
[DataMemberAttribute]
public long EcoResCategoryAttributeLookup { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESCATEGORYATTRIBUTELOOKUP")]
[DataMemberAttribute]
public:
property long long EcoResCategoryAttributeLookup {
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

