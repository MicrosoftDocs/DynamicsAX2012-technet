---
title: ProductChangeTrackingAnchorSet.EcoResReferenceValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResReferenceValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResReferenceValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresreferencevalue(v=AX.60)
ms:contentKeyID: 62202278
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResReferenceValue
dev_langs:
- CSharp
- C++
- VB
---

# EcoResReferenceValue Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESREFERENCEVALUE")> _
Public Property EcoResReferenceValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResReferenceValue

instance.EcoResReferenceValue = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESREFERENCEVALUE")]
public long EcoResReferenceValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESREFERENCEVALUE")]
public:
property long long EcoResReferenceValue {
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

