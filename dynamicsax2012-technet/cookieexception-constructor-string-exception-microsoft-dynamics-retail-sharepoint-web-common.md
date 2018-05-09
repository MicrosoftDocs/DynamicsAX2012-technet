---
title: CookieException Constructor (String, Exception) (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: CookieException Constructor (String, Exception)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieException.#ctor(System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.cookieexception.cookieexception(v=AX.60)
ms:contentKeyID: 62204609
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CookieException Constructor (String, Exception)

Initializes a new instance of the [CookieException](cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    message As String, _
    innerException As Exception _
)
'Usage
Dim message As String
Dim innerException As Exception

Dim instance As New CookieException(message, _
    innerException)
```

``` csharp
public CookieException(
    string message,
    Exception innerException
)
```

``` c++
public:
CookieException(
    String^ message, 
    Exception^ innerException
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - innerException  
    Type: [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[CookieException Class](cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[CookieException Overload](cookieexception-constructor-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

