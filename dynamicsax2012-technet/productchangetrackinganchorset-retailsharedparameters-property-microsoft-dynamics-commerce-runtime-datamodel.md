---
title: ProductChangeTrackingAnchorSet.RetailSharedParameters Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailSharedParameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailSharedParameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailsharedparameters(v=AX.60)
ms:contentKeyID: 62208119
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailSharedParameters
dev_langs:
- CSharp
- C++
- VB
---

# RetailSharedParameters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILSHAREDPARAMETERS")> _
Public Property RetailSharedParameters As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailSharedParameters

instance.RetailSharedParameters = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILSHAREDPARAMETERS")]
public long RetailSharedParameters { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILSHAREDPARAMETERS")]
public:
property long long RetailSharedParameters {
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

