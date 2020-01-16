---
title: ProductManager.GetProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getproducts(v=AX.60)
ms:contentKeyID: 65321563
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetProducts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetProducts ( _
    querySettings As QueryResultSettings _
) As PagedResult(Of Product)
'Usage
Dim instance As ProductManager
Dim querySettings As QueryResultSettings
Dim returnValue As PagedResult(Of Product)

returnValue = instance.GetProducts(querySettings)
```

``` csharp
public PagedResult<Product> GetProducts(
    QueryResultSettings querySettings
)
```

``` c++
public:
PagedResult<Product^>^ GetProducts(
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

