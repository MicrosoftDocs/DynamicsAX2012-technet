---
title: ProductPrice.ListingId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ListingId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ListingId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.listingid(v=AX.60)
ms:contentKeyID: 62211986
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ListingId
dev_langs:
- CSharp
- C++
- VB
---

# ListingId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingId As Long
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As Long

value = instance.ListingId

instance.ListingId = value
```

``` csharp
[DataMemberAttribute]
public long ListingId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ListingId {
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

