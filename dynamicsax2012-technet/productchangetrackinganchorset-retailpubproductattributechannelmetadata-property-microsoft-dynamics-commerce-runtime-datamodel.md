---
title: ProductChangeTrackingAnchorSet.RetailPubProductAttributeChannelMetadata Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailPubProductAttributeChannelMetadata Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubProductAttributeChannelMetadata
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailpubproductattributechannelmetadata(v=AX.60)
ms:contentKeyID: 62208827
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubProductAttributeChannelMetadata
dev_langs:
- CSharp
- C++
- VB
---

# RetailPubProductAttributeChannelMetadata Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILPUBPRODUCTATTRIBUTECHANNELMETADATA")> _
Public Property RetailPubProductAttributeChannelMetadata As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailPubProductAttributeChannelMetadata

instance.RetailPubProductAttributeChannelMetadata = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILPUBPRODUCTATTRIBUTECHANNELMETADATA")]
public long RetailPubProductAttributeChannelMetadata { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILPUBPRODUCTATTRIBUTECHANNELMETADATA")]
public:
property long long RetailPubProductAttributeChannelMetadata {
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

