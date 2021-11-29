---
title: Authentication.RequiresAssociation Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RequiresAssociation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Authentication.RequiresAssociation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.authentication.requiresassociation(v=AX.60)
ms:contentKeyID: 62202309
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Authentication.RequiresAssociation
dev_langs:
- CSharp
- C++
- VB
---

# RequiresAssociation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether this control requires the logged in user to be associated to an AX customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Property RequiresAssociation As Boolean
    Get
    Set
'Usage
Dim instance As Authentication
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

[Authentication Class](authentication-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

