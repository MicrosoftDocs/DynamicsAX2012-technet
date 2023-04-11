---
title: ProductChangeTrackingAnchorSet.EcoResDateTimeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResDateTimeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResDateTimeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresdatetimevalue(v=AX.60)
ms:contentKeyID: 62209317
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResDateTimeValue
dev_langs:
- CSharp
- C++
- VB
---

# EcoResDateTimeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESDATETIMEVALUE")> _
<DataMemberAttribute> _
Public Property EcoResDateTimeValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResDateTimeValue

instance.EcoResDateTimeValue = value
```

``` csharp
[ColumnAttribute("ECORESDATETIMEVALUE")]
[DataMemberAttribute]
public long EcoResDateTimeValue { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESDATETIMEVALUE")]
[DataMemberAttribute]
public:
property long long EcoResDateTimeValue {
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

