---
title: ProductChangeTrackingAnchorSet.EcoResConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresconfiguration(v=AX.60)
ms:contentKeyID: 62214810
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# EcoResConfiguration Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESCONFIGURATION")> _
Public Property EcoResConfiguration As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResConfiguration

instance.EcoResConfiguration = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESCONFIGURATION")]
public long EcoResConfiguration { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESCONFIGURATION")]
public:
property long long EcoResConfiguration {
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

