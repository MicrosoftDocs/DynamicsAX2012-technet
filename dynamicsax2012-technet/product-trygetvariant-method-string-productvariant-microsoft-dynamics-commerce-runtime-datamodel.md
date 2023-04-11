---
title: Product.TryGetVariant Method (String, ProductVariant) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TryGetVariant Method (String, ProductVariant)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.TryGetVariant(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.trygetvariant(v=AX.60)
ms:contentKeyID: 62209205
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TryGetVariant Method (String, ProductVariant)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Attempts to return the variant with the specified inventory dimension id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetVariant ( _
    inventDimId As String, _
    <OutAttribute> ByRef variant As ProductVariant _
) As Boolean
'Usage
Dim instance As Product
Dim inventDimId As String
Dim variant As ProductVariant
Dim returnValue As Boolean

returnValue = instance.TryGetVariant(inventDimId, _
    variant)
```

``` csharp
public bool TryGetVariant(
    string inventDimId,
    out ProductVariant variant
)
```

``` c++
public:
bool TryGetVariant(
    String^ inventDimId, 
    [OutAttribute] ProductVariant^% variant
)
```

#### Parameters

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

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

