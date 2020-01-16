---
title: GetRemoteProductsByCategoryServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetRemoteProductsByCategoryServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByCategoryServiceRequest.#ctor(System.Int64,System.Nullable{System.Int64},System.Int64,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getremoteproductsbycategoryservicerequest.getremoteproductsbycategoryservicerequest(v=AX.60)
ms:contentKeyID: 65319313
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByCategoryServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetRemoteProductsByCategoryServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    catalogId As Nullable(Of Long), _
    categoryId As Long, _
    attributeIds As String, _
    includeProductsFromDescendantCategories As Boolean _
)
'Usage
Dim channelId As Long
Dim catalogId As Nullable(Of Long)
Dim categoryId As Long
Dim attributeIds As String
Dim includeProductsFromDescendantCategories As Boolean

Dim instance As New GetRemoteProductsByCategoryServiceRequest(channelId, _
    catalogId, categoryId, attributeIds, _
    includeProductsFromDescendantCategories)
```

``` csharp
public GetRemoteProductsByCategoryServiceRequest(
    long channelId,
    Nullable<long> catalogId,
    long categoryId,
    string attributeIds,
    bool includeProductsFromDescendantCategories
)
```

``` c++
public:
GetRemoteProductsByCategoryServiceRequest(
    long long channelId, 
    Nullable<long long> catalogId, 
    long long categoryId, 
    String^ attributeIds, 
    bool includeProductsFromDescendantCategories
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - categoryId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - attributeIds  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeProductsFromDescendantCategories  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetRemoteProductsByCategoryServiceRequest Class](getremoteproductsbycategoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

