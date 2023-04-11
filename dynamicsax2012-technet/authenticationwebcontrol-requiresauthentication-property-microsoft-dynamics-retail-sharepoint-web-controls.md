---
title: AuthenticationWebControl.RequiresAuthentication Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: RequiresAuthentication Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AuthenticationWebControl.RequiresAuthentication
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.authenticationwebcontrol.requiresauthentication(v=AX.60)
ms:contentKeyID: 62203301
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AuthenticationWebControl.RequiresAuthentication
dev_langs:
- CSharp
- C++
- VB
---

# RequiresAuthentication Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether this control requires the user to be logged in.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property RequiresAuthentication As Boolean
    Get
    Set
'Usage
Dim instance As AuthenticationWebControl
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

[AuthenticationWebControl Class](authenticationwebcontrol-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

