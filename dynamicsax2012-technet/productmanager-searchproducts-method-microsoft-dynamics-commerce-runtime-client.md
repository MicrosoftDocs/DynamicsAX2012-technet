---
title: ProductManager.SearchProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SearchProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.SearchProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.searchproducts(v=AX.60)
ms:contentKeyID: 65321040
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.SearchProducts
dev_langs:
- CSharp
- C++
- VB
---

# SearchProducts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SearchProducts ( _
    criteria As ProductSearchCriteria, _
    settings As QueryResultSettings _
) As ProductSearchResult
'Usage
Dim instance As ProductManager
Dim criteria As ProductSearchCriteria
Dim settings As QueryResultSettings
Dim returnValue As ProductSearchResult

returnValue = instance.SearchProducts(criteria, _
    settings)
```

``` csharp
public ProductSearchResult SearchProducts(
    ProductSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
ProductSearchResult^ SearchProducts(
    ProductSearchCriteria^ criteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

