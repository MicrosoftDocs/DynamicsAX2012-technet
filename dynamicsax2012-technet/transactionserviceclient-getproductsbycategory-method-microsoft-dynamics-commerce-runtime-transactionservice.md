---
title: TransactionServiceClient.GetProductsByCategory Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetProductsByCategory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductsByCategory(System.Int64,System.Int64,System.Int64,System.Int64,System.Int32,System.Int32,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getproductsbycategory(v=AX.60)
ms:contentKeyID: 65322017
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductsByCategory
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsByCategory Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductsByCategory ( _
    currentChannelId As Long, _
    targetChannelId As Long, _
    targetCatalogId As Long, _
    targetCategoryId As Long, _
    skip As Integer, _
    top As Integer, _
    attributeIds As String, _
    includeProductsFromDescendantCategories As Boolean _
) As ReadOnlyCollection(Of Product)
'Usage
Dim instance As TransactionServiceClient
Dim currentChannelId As Long
Dim targetChannelId As Long
Dim targetCatalogId As Long
Dim targetCategoryId As Long
Dim skip As Integer
Dim top As Integer
Dim attributeIds As String
Dim includeProductsFromDescendantCategories As Boolean
Dim returnValue As ReadOnlyCollection(Of Product)

returnValue = instance.GetProductsByCategory(currentChannelId, _
    targetChannelId, targetCatalogId, _
    targetCategoryId, skip, top, attributeIds, _
    includeProductsFromDescendantCategories)
```

``` csharp
public ReadOnlyCollection<Product> GetProductsByCategory(
    long currentChannelId,
    long targetChannelId,
    long targetCatalogId,
    long targetCategoryId,
    int skip,
    int top,
    string attributeIds,
    bool includeProductsFromDescendantCategories
)
```

``` c++
public:
ReadOnlyCollection<Product^>^ GetProductsByCategory(
    long long currentChannelId, 
    long long targetChannelId, 
    long long targetCatalogId, 
    long long targetCategoryId, 
    int skip, 
    int top, 
    String^ attributeIds, 
    bool includeProductsFromDescendantCategories
)
```

#### Parameters

  - currentChannelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - targetChannelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - targetCatalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - targetCategoryId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - skip  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - top  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - attributeIds  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeProductsFromDescendantCategories  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

