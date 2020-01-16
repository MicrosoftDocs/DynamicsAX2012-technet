---
title: Listing.CreateStatusSuccessfullyDeleted Method  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: CreateStatusSuccessfullyDeleted Method
ms:assetid: M:Microsoft.Dynamics.Retail.Channels.Listing.CreateStatusSuccessfullyDeleted(System.Int64,System.Int64,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.createstatussuccessfullydeleted(v=AX.60)
ms:contentKeyID: 65318077
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.CreateStatusSuccessfullyDeleted
dev_langs:
- CSharp
- C++
- VB
---

# CreateStatusSuccessfullyDeleted Method

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateStatusSuccessfullyDeleted ( _
    channelId As Long, _
    catalogId As Long, _
    productId As Long, _
    languageId As String _
) As ListingPublishStatus
'Usage
Dim channelId As Long
Dim catalogId As Long
Dim productId As Long
Dim languageId As String
Dim returnValue As ListingPublishStatus

returnValue = Listing.CreateStatusSuccessfullyDeleted(channelId, _
    catalogId, productId, languageId)
```

``` csharp
public static ListingPublishStatus CreateStatusSuccessfullyDeleted(
    long channelId,
    long catalogId,
    long productId,
    string languageId
)
```

``` c++
public:
static ListingPublishStatus^ CreateStatusSuccessfullyDeleted(
    long long channelId, 
    long long catalogId, 
    long long productId, 
    String^ languageId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: ListingPublishStatus  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

