---
title: ProductDataManager.EndReadChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: EndReadChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.EndReadChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.endreadchangedproducts(v=AX.60)
ms:contentKeyID: 62203913
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.EndReadChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# EndReadChangedProducts Method

Ends session used to read changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub EndReadChangedProducts ( _
    session As ReadChangedProductsSession _
)
'Usage
Dim instance As ProductDataManager
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

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

