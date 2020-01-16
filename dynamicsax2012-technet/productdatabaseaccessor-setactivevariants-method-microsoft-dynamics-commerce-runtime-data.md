---
title: ProductDatabaseAccessor.SetActiveVariants Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SetActiveVariants Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.SetActiveVariants(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.setactivevariants(v=AX.60)
ms:contentKeyID: 65319418
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.SetActiveVariants
dev_langs:
- CSharp
- C++
- VB
---

# SetActiveVariants Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetActiveVariants ( _
    searchCriteria As ProductSearchCriteria, _
    searchResult As ProductSearchResult _
)
'Usage
Dim searchCriteria As ProductSearchCriteria
Dim searchResult As ProductSearchResult

ProductDatabaseAccessor.SetActiveVariants(searchCriteria, _
    searchResult)
```

``` csharp
public static void SetActiveVariants(
    ProductSearchCriteria searchCriteria,
    ProductSearchResult searchResult
)
```

``` c++
public:
static void SetActiveVariants(
    ProductSearchCriteria^ searchCriteria, 
    ProductSearchResult^ searchResult
)
```

#### Parameters

  - searchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - searchResult  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

