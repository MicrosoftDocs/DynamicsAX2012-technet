---
title: ProductManager.BeginReadChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: BeginReadChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.BeginReadChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.beginreadchangedproducts(v=AX.60)
ms:contentKeyID: 62210766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.BeginReadChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# BeginReadChangedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Begins session to read changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function BeginReadChangedProducts ( _
    searchCriteria As ChangedProductsSearchCriteria _
) As ReadChangedProductsSession
'Usage
Dim instance As ProductManager
Dim searchCriteria As ChangedProductsSearchCriteria
Dim returnValue As ReadChangedProductsSession

returnValue = instance.BeginReadChangedProducts(searchCriteria)
```

``` csharp
public ReadChangedProductsSession BeginReadChangedProducts(
    ChangedProductsSearchCriteria searchCriteria
)
```

``` c++
public:
ReadChangedProductsSession^ BeginReadChangedProducts(
    ChangedProductsSearchCriteria^ searchCriteria
)
```

#### Parameters

  - searchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The session.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

