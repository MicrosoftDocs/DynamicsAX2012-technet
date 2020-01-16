---
title: ProductDataManager.BeginReadChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BeginReadChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.BeginReadChangedProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.beginreadchangedproducts(v=AX.60)
ms:contentKeyID: 62210059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.BeginReadChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# BeginReadChangedProducts Method

Creates a session to be used while reading changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function BeginReadChangedProducts ( _
    queryCriteria As ChangedProductsSearchCriteria _
) As ReadChangedProductsSession
'Usage
Dim instance As ProductDataManager
Dim queryCriteria As ChangedProductsSearchCriteria
Dim returnValue As ReadChangedProductsSession

returnValue = instance.BeginReadChangedProducts(queryCriteria)
```

``` csharp
public ReadChangedProductsSession BeginReadChangedProducts(
    ChangedProductsSearchCriteria queryCriteria
)
```

``` c++
public:
ReadChangedProductsSession^ BeginReadChangedProducts(
    ChangedProductsSearchCriteria^ queryCriteria
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The session.  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

