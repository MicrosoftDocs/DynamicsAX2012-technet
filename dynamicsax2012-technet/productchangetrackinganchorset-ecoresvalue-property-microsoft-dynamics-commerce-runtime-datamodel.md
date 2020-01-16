---
title: ProductChangeTrackingAnchorSet.EcoResValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresvalue(v=AX.60)
ms:contentKeyID: 62208291
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResValue
dev_langs:
- CSharp
- C++
- VB
---

# EcoResValue Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESVALUE")> _
Public Property EcoResValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResValue

instance.EcoResValue = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESVALUE")]
public long EcoResValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESVALUE")]
public:
property long long EcoResValue {
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

