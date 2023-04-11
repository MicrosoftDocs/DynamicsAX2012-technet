---
title: ProductVariantInformation Constructor (String, Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantInformation Constructor (String, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.#ctor(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.productvariantinformation(v=AX.60)
ms:contentKeyID: 62213824
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductVariantInformation Constructor (String, Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductVariantInformation](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    productId As Long _
)
'Usage
Dim itemId As String
Dim productId As Long

Dim instance As New ProductVariantInformation(itemId, _
    productId)
```

``` csharp
public ProductVariantInformation(
    string itemId,
    long productId
)
```

``` c++
public:
ProductVariantInformation(
    String^ itemId, 
    long long productId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductVariantInformation Overload](productvariantinformation-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

