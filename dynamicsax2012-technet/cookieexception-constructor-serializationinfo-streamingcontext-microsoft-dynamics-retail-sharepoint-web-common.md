---
title: CookieException Constructor (SerializationInfo, StreamingContext) (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: CookieException Constructor (SerializationInfo, StreamingContext)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.cookieexception.cookieexception(v=AX.60)
ms:contentKeyID: 62204308
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CookieException Constructor (SerializationInfo, StreamingContext)

Initializes a new instance of the [CookieException](cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    serializationInfo As SerializationInfo, _
    streamingContext As StreamingContext _
)
'Usage
Dim serializationInfo As SerializationInfo
Dim streamingContext As StreamingContext

Dim instance As New CookieException(serializationInfo, _
    streamingContext)
```

``` csharp
protected CookieException(
    SerializationInfo serializationInfo,
    StreamingContext streamingContext
)
```

``` c++
protected:
CookieException(
    SerializationInfo^ serializationInfo, 
    StreamingContext streamingContext
)
```

#### Parameters

  - serializationInfo  
    Type: [System.Runtime.Serialization.SerializationInfo](https://technet.microsoft.com/en-us/library/a9b6042e\(v=ax.60\))  

<!-- end list -->

  - streamingContext  
    Type: [System.Runtime.Serialization.StreamingContext](https://technet.microsoft.com/en-us/library/t16abws5\(v=ax.60\))  

## See Also

#### Reference

[CookieException Class](cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[CookieException Overload](cookieexception-constructor-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

