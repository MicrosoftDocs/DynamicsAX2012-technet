---
title: Product.TryGetVariant Method (Int64, ProductVariant) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TryGetVariant Method (Int64, ProductVariant)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.TryGetVariant(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.trygetvariant(v=AX.60)
ms:contentKeyID: 62210482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TryGetVariant Method (Int64, ProductVariant)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Attempts to return the variant with the specified id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetVariant ( _
    variantId As Long, _
    <OutAttribute> ByRef variant As ProductVariant _
) As Boolean
'Usage
Dim instance As Product
Dim variantId As Long
Dim variant As ProductVariant
Dim returnValue As Boolean

returnValue = instance.TryGetVariant(variantId, _
    variant)
```

``` csharp
public bool TryGetVariant(
    long variantId,
    out ProductVariant variant
)
```

``` c++
public:
bool TryGetVariant(
    long long variantId, 
    [OutAttribute] ProductVariant^% variant
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the product is a master, and the specified variant identifier is valid; false otherwise.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[TryGetVariant Overload](product-trygetvariant-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

