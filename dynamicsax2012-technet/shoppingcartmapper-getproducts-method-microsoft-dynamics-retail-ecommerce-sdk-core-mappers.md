---
title: ShoppingCartMapper.GetProducts Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers)
TOCTitle: GetProducts Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.ShoppingCartMapper.GetProducts(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.mappers.shoppingcartmapper.getproducts(v=AX.60)
ms:contentKeyID: 65316840
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.ShoppingCartMapper.GetProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Function GetProducts ( _
    productIds As IEnumerable(Of Long) _
) As IEnumerable(Of Product)
'Usage
Dim instance As ShoppingCartMapper
Dim productIds As IEnumerable(Of Long)
Dim returnValue As IEnumerable(Of Product)

returnValue = instance.GetProducts(productIds)
```

``` csharp
public IEnumerable<Product> GetProducts(
    IEnumerable<long> productIds
)
```

``` c++
public:
IEnumerable<Product^>^ GetProducts(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Product\>  

## See Also

#### Reference

[ShoppingCartMapper Class](shoppingcartmapper-class-microsoft-dynamics-retail-ecommerce-sdk-core-mappers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)

