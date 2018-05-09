---
title: GetRemoteProductsByKeywordServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetRemoteProductsByKeywordServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByKeywordServiceRequest.#ctor(System.Int64,System.Nullable{System.Int64},System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getremoteproductsbykeywordservicerequest.getremoteproductsbykeywordservicerequest(v=AX.60)
ms:contentKeyID: 65318958
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByKeywordServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetRemoteProductsByKeywordServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    catalogId As Nullable(Of Long), _
    keywords As String, _
    attributeIds As String _
)
'Usage
Dim channelId As Long
Dim catalogId As Nullable(Of Long)
Dim keywords As String
Dim attributeIds As String

Dim instance As New GetRemoteProductsByKeywordServiceRequest(channelId, _
    catalogId, keywords, attributeIds)
```

``` csharp
public GetRemoteProductsByKeywordServiceRequest(
    long channelId,
    Nullable<long> catalogId,
    string keywords,
    string attributeIds
)
```

``` c++
public:
GetRemoteProductsByKeywordServiceRequest(
    long long channelId, 
    Nullable<long long> catalogId, 
    String^ keywords, 
    String^ attributeIds
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - keywords  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - attributeIds  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetRemoteProductsByKeywordServiceRequest Class](getremoteproductsbykeywordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

