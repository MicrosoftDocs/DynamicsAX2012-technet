---
title: RelatedProduct.ProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.ProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.productrecordid(v=AX.60)
ms:contentKeyID: 62206208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.ProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Product record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCT")> _
Public Property ProductRecordId As Long
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As Long

value = instance.ProductRecordId

instance.ProductRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCT")]
public long ProductRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCT")]
public:
property long long ProductRecordId {
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

