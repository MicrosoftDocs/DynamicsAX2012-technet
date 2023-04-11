---
title: Authentication.RequiresAuthentication Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RequiresAuthentication Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Authentication.RequiresAuthentication
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.authentication.requiresauthentication(v=AX.60)
ms:contentKeyID: 62206353
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Authentication.RequiresAuthentication
dev_langs:
- CSharp
- C++
- VB
---

# RequiresAuthentication Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether this control requires the user to be logged in.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Property RequiresAuthentication As Boolean
    Get
    Set
'Usage
Dim instance As Authentication
Dim value As Boolean

value = instance.RequiresAuthentication

instance.RequiresAuthentication = value
```

``` csharp
public bool RequiresAuthentication { get; set; }
```

``` c++
public:
property bool RequiresAuthentication {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Authentication Class](authentication-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

