---
title: ProductChangeTrackingAnchorSet.RetailPubProductAttributeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailPubProductAttributeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubProductAttributeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.retailpubproductattributevalue(v=AX.60)
ms:contentKeyID: 62212655
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.RetailPubProductAttributeValue
dev_langs:
- CSharp
- C++
- VB
---

# RetailPubProductAttributeValue Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETAILPUBPRODUCTATTRIBUTEVALUE")> _
<DataMemberAttribute> _
Public Property RetailPubProductAttributeValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.RetailPubProductAttributeValue

instance.RetailPubProductAttributeValue = value
```

``` csharp
[ColumnAttribute("RETAILPUBPRODUCTATTRIBUTEVALUE")]
[DataMemberAttribute]
public long RetailPubProductAttributeValue { get; set; }
```

``` c++
[ColumnAttribute(L"RETAILPUBPRODUCTATTRIBUTEVALUE")]
[DataMemberAttribute]
public:
property long long RetailPubProductAttributeValue {
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

