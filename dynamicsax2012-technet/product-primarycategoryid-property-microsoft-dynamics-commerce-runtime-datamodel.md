---
title: Product.PrimaryCategoryId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrimaryCategoryId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.PrimaryCategoryId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.primarycategoryid(v=AX.60)
ms:contentKeyID: 62209090
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.PrimaryCategoryId
dev_langs:
- CSharp
- C++
- VB
---

# PrimaryCategoryId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the primary category specified for the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PrimaryCategoryId As Long
    Get
    Set
'Usage
Dim instance As Product
Dim value As Long

value = instance.PrimaryCategoryId

instance.PrimaryCategoryId = value
```

``` csharp
[DataMemberAttribute]
public long PrimaryCategoryId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long PrimaryCategoryId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

