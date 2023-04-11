---
title: GeoLocationNotFoundException Constructor (String, Exception) (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GeoLocationNotFoundException Constructor (String, Exception)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.GeoLocationNotFoundException.#ctor(System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.geolocationnotfoundexception.geolocationnotfoundexception(v=AX.60)
ms:contentKeyID: 62204107
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GeoLocationNotFoundException Constructor (String, Exception)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GeoLocationNotFoundException](geolocationnotfoundexception-class-microsoft-dynamics-retail-sharepoint-web-services.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    message As String, _
    inner As Exception _
)
'Usage
Dim message As String
Dim inner As Exception

Dim instance As New GeoLocationNotFoundException(message, _
    inner)
```

``` csharp
public GeoLocationNotFoundException(
    string message,
    Exception inner
)
```

``` c++
public:
GeoLocationNotFoundException(
    String^ message, 
    Exception^ inner
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inner  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[GeoLocationNotFoundException Class](geolocationnotfoundexception-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[GeoLocationNotFoundException Overload](geolocationnotfoundexception-constructor-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

