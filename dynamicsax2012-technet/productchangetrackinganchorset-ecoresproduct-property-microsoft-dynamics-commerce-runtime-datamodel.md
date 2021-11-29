---
title: ProductChangeTrackingAnchorSet.EcoResProduct Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResProduct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProduct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresproduct(v=AX.60)
ms:contentKeyID: 62208759
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProduct
dev_langs:
- CSharp
- C++
- VB
---

# EcoResProduct Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESPRODUCT")> _
<DataMemberAttribute> _
Public Property EcoResProduct As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResProduct

instance.EcoResProduct = value
```

``` csharp
[ColumnAttribute("ECORESPRODUCT")]
[DataMemberAttribute]
public long EcoResProduct { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESPRODUCT")]
[DataMemberAttribute]
public:
property long long EcoResProduct {
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

