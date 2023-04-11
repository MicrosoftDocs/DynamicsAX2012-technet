---
title: TransactionServiceClient.GetProductsByKeyword Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetProductsByKeyword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductsByKeyword(System.Int64,System.Int64,System.Int64,System.String,System.Int32,System.Int32,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getproductsbykeyword(v=AX.60)
ms:contentKeyID: 62210389
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductsByKeyword
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsByKeyword Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the products matching the specified search keywords.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductsByKeyword ( _
    currentChannelId As Long, _
    targetChannelId As Long, _
    targetCatalogId As Long, _
    keyword As String, _
    skip As Integer, _
    top As Integer, _
    attributeIds As String _
) As ReadOnlyCollection(Of Product)
'Usage
Dim instance As TransactionServiceClient
Dim currentChannelId As Long
Dim targetChannelId As Long
Dim targetCatalogId As Long
Dim keyword As String
Dim skip As Integer
Dim top As Integer
Dim attributeIds As String
Dim returnValue As ReadOnlyCollection(Of Product)

returnValue = instance.GetProductsByKeyword(currentChannelId, _
    targetChannelId, targetCatalogId, _
    keyword, skip, top, attributeIds)
```

``` csharp
public ReadOnlyCollection<Product> GetProductsByKeyword(
    long currentChannelId,
    long targetChannelId,
    long targetCatalogId,
    string keyword,
    int skip,
    int top,
    string attributeIds
)
```

``` c++
public:
ReadOnlyCollection<Product^>^ GetProductsByKeyword(
    long long currentChannelId, 
    long long targetChannelId, 
    long long targetCatalogId, 
    String^ keyword, 
    int skip, 
    int top, 
    String^ attributeIds
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

  - keyword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - skip  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - top  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - attributeIds  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of products matching the specified search keywords.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

