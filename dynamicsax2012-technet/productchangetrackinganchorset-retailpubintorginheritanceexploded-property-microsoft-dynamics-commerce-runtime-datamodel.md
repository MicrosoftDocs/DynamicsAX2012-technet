---
title: ProductChangeTrackingAnchorSet.RetailPubIntOrgInheritanceExploded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailPubIntOrgInheritanceExploded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubIntOrgInheritanceExploded
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailpubintorginheritanceexploded(v=AX.60)
ms:contentKeyID: 62208654
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubIntOrgInheritanceExploded
dev_langs:
- CSharp
- C++
- VB
---

# RetailPubIntOrgInheritanceExploded Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETAILPUBINTORGINHERITANCEEXPLODED")> _
<DataMemberAttribute> _
Public Property RetailPubIntOrgInheritanceExploded As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailPubIntOrgInheritanceExploded

instance.RetailPubIntOrgInheritanceExploded = value
```

``` csharp
[ColumnAttribute("RETAILPUBINTORGINHERITANCEEXPLODED")]
[DataMemberAttribute]
public long RetailPubIntOrgInheritanceExploded { get; set; }
```

``` c++
[ColumnAttribute(L"RETAILPUBINTORGINHERITANCEEXPLODED")]
[DataMemberAttribute]
public:
property long long RetailPubIntOrgInheritanceExploded {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

