---
title: RelatedProduct.RelatedProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RelatedProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.RelatedProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.relatedproductrecordid(v=AX.60)
ms:contentKeyID: 62201763
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.RelatedProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# RelatedProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the related Product record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RELATEDPRODUCT")> _
Public Property RelatedProductRecordId As Long
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As Long

value = instance.RelatedProductRecordId

instance.RelatedProductRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RELATEDPRODUCT")]
public long RelatedProductRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RELATEDPRODUCT")]
public:
property long long RelatedProductRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RelatedProduct Class](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

