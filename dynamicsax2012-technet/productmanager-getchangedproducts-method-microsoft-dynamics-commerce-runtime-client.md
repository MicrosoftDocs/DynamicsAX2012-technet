---
title: ProductManager.GetChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getchangedproducts(v=AX.60)
ms:contentKeyID: 65317855
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetChangedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChangedProducts ( _
    queryCriteria As ChangedProductsSearchCriteria, _
    querySettings As QueryResultSettings _
) As ChangedProductsSearchResult
'Usage
Dim instance As ProductManager
Dim queryCriteria As ChangedProductsSearchCriteria
Dim querySettings As QueryResultSettings
Dim returnValue As ChangedProductsSearchResult

returnValue = instance.GetChangedProducts(queryCriteria, _
    querySettings)
```

``` csharp
public ChangedProductsSearchResult GetChangedProducts(
    ChangedProductsSearchCriteria queryCriteria,
    QueryResultSettings querySettings
)
```

``` c++
public:
ChangedProductsSearchResult^ GetChangedProducts(
    ChangedProductsSearchCriteria^ queryCriteria, 
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

