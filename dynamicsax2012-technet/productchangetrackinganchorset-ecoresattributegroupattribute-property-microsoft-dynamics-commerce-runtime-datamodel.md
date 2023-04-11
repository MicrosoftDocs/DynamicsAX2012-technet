---
title: ProductChangeTrackingAnchorSet.EcoResAttributeGroupAttribute Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResAttributeGroupAttribute Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResAttributeGroupAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresattributegroupattribute(v=AX.60)
ms:contentKeyID: 62209877
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResAttributeGroupAttribute
dev_langs:
- CSharp
- C++
- VB
---

# EcoResAttributeGroupAttribute Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESATTRIBUTEGROUPATTRIBUTE")> _
Public Property EcoResAttributeGroupAttribute As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResAttributeGroupAttribute

instance.EcoResAttributeGroupAttribute = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESATTRIBUTEGROUPATTRIBUTE")]
public long EcoResAttributeGroupAttribute { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESATTRIBUTEGROUPATTRIBUTE")]
public:
property long long EcoResAttributeGroupAttribute {
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

