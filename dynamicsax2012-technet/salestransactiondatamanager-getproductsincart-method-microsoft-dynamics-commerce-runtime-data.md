---
title: SalesTransactionDataManager.GetProductsInCart Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductsInCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetProductsInCart(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.getproductsincart(v=AX.60)
ms:contentKeyID: 62213191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetProductsInCart
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsInCart Method

Gets the list of products used in context of the cart specified by the cart identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductsInCart ( _
    cartId As String _
) As ProductSearchResult
'Usage
Dim instance As SalesTransactionDataManager
Dim cartId As String
Dim returnValue As ProductSearchResult

returnValue = instance.GetProductsInCart(cartId)
```

``` csharp
public ProductSearchResult GetProductsInCart(
    string cartId
)
```

``` c++
public:
ProductSearchResult^ GetProductsInCart(
    String^ cartId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns collection of product objects.  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

