---
title: AuthenticationWebControl.RequiresAssociation Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: RequiresAssociation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AuthenticationWebControl.RequiresAssociation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.authenticationwebcontrol.requiresassociation(v=AX.60)
ms:contentKeyID: 62202703
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AuthenticationWebControl.RequiresAssociation
dev_langs:
- CSharp
- C++
- VB
---

# RequiresAssociation Property

Gets or sets whether this control requires the logged in user to be associated to an AX customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property RequiresAssociation As Boolean
    Get
    Set
'Usage
Dim instance As AuthenticationWebControl
Dim value As Boolean

value = instance.RequiresAssociation

instance.RequiresAssociation = value
```

``` csharp
public bool RequiresAssociation { get; set; }
```

``` c++
public:
property bool RequiresAssociation {
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

