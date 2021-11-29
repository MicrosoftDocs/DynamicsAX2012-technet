---
title: ProductPrice.ProductLookupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductLookupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ProductLookupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.productlookupid(v=AX.60)
ms:contentKeyID: 62214650
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ProductLookupId
dev_langs:
- CSharp
- C++
- VB
---

# ProductLookupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product identifier corresponding to this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCTLOOKUPID")> _
<DataMemberAttribute> _
Public Property ProductLookupId As Long
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As Long

value = instance.ProductLookupId

instance.ProductLookupId = value
```

``` csharp
[ColumnAttribute("PRODUCTLOOKUPID")]
[DataMemberAttribute]
public long ProductLookupId { get; set; }
```

``` c++
[ColumnAttribute(L"PRODUCTLOOKUPID")]
[DataMemberAttribute]
public:
property long long ProductLookupId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

