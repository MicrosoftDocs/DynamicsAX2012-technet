---
title: ProductManager.VerifyProductExistence Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: VerifyProductExistence Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.VerifyProductExistence(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.verifyproductexistence(v=AX.60)
ms:contentKeyID: 62208400
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.VerifyProductExistence
dev_langs:
- CSharp
- C++
- VB
---

# VerifyProductExistence Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies products existence.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function VerifyProductExistence ( _
    criteria As ProductExistenceCriteria _
) As ReadOnlyCollection(Of ProductExistenceId)
'Usage
Dim instance As ProductManager
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
List of verified IDs.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

