---
title: FacebookConnector.Me Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: Me Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.Me
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookconnector.me(v=AX.60)
ms:contentKeyID: 62204290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.Me
dev_langs:
- CSharp
- C++
- VB
---

# Me Method

Get current Facebook user info.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Function Me As FacebookUser
'Usage
Dim instance As FacebookConnector
Dim returnValue As FacebookUser

returnValue = instance.Me()
```

``` csharp
public FacebookUser Me()
```

``` c++
public:
FacebookUser^ Me()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookUser](facebookuser-class-microsoft-dynamics-retail-sharepoint-web-common.md)  
The current Facebook user info.  

## See Also

#### Reference

[FacebookConnector Class](facebookconnector-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

