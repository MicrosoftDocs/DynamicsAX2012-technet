---
title: ProductChangeTrackingAnchorSet.RetailPubRetailChannelTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailPubRetailChannelTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubRetailChannelTable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailpubretailchanneltable(v=AX.60)
ms:contentKeyID: 62203497
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubRetailChannelTable
dev_langs:
- CSharp
- C++
- VB
---

# RetailPubRetailChannelTable Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILPUBRETAILCHANNELTABLE")> _
Public Property RetailPubRetailChannelTable As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailPubRetailChannelTable

instance.RetailPubRetailChannelTable = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILPUBRETAILCHANNELTABLE")]
public long RetailPubRetailChannelTable { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILPUBRETAILCHANNELTABLE")]
public:
property long long RetailPubRetailChannelTable {
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

