---
title: ProductDataManager.VerifyProductExistence Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: VerifyProductExistence Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.VerifyProductExistence(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.verifyproductexistence(v=AX.60)
ms:contentKeyID: 62215184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.VerifyProductExistence
dev_langs:
- CSharp
- C++
- VB
---

# VerifyProductExistence Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies existence of products by given composite IDs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function VerifyProductExistence ( _
    criteria As ProductExistenceCriteria _
) As ReadOnlyCollection(Of ProductExistenceId)
'Usage
Dim instance As ProductDataManager
Dim criteria As ProductExistenceCriteria
Dim returnValue As ReadOnlyCollection(Of ProductExistenceId)

returnValue = instance.VerifyProductExistence(criteria)
```

``` csharp
public ReadOnlyCollection<ProductExistenceId> VerifyProductExistence(
    ProductExistenceCriteria criteria
)
```

``` c++
public:
ReadOnlyCollection<ProductExistenceId^>^ VerifyProductExistence(
    ProductExistenceCriteria^ criteria
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductExistenceId](productexistenceid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of verified IDs.  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

