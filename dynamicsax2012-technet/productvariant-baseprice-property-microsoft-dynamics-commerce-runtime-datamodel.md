---
title: ProductVariant.BasePrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BasePrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.BasePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.baseprice(v=AX.60)
ms:contentKeyID: 62212343
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.BasePrice
dev_langs:
- CSharp
- C++
- VB
---

# BasePrice Property

Gets the base sales price for the listing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BasePrice As Decimal
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As Decimal

value = instance.BasePrice

instance.BasePrice = value
```

``` csharp
[DataMemberAttribute]
public decimal BasePrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal BasePrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

