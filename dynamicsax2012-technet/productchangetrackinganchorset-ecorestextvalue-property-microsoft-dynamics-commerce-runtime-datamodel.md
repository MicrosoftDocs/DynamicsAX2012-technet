---
title: ProductChangeTrackingAnchorSet.EcoResTextValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResTextValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResTextValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecorestextvalue(v=AX.60)
ms:contentKeyID: 62207727
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResTextValue
dev_langs:
- CSharp
- C++
- VB
---

# EcoResTextValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESTEXTVALUE")> _
Public Property EcoResTextValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResTextValue

instance.EcoResTextValue = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESTEXTVALUE")]
public long EcoResTextValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESTEXTVALUE")]
public:
property long long EcoResTextValue {
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

