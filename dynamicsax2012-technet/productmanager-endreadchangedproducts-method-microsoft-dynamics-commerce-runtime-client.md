---
title: ProductManager.EndReadChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: EndReadChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.EndReadChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.endreadchangedproducts(v=AX.60)
ms:contentKeyID: 62205944
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.EndReadChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# EndReadChangedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Ends session to read changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub EndReadChangedProducts ( _
    session As ReadChangedProductsSession _
)
'Usage
Dim instance As ProductManager
Dim session As ReadChangedProductsSession

instance.EndReadChangedProducts(session)
```

``` csharp
public void EndReadChangedProducts(
    ReadChangedProductsSession session
)
```

``` c++
public:
void EndReadChangedProducts(
    ReadChangedProductsSession^ session
)
```

#### Parameters

  - session  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

