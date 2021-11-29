---
title: Global.Application_BeginRequest Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront)
TOCTitle: Application_BeginRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Global.Application_BeginRequest(System.Object,System.EventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.global.application_beginrequest(v=AX.60)
ms:contentKeyID: 62206963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Global.Application_BeginRequest
dev_langs:
- CSharp
- C++
- VB
---

# Application\_BeginRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the BeginRequest event of the Application control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub Application_BeginRequest ( _
    sender As Object, _
    e As EventArgs _
)
'Usage
Dim instance As Global
Dim sender As Object
Dim e As EventArgs

instance.Application_BeginRequest(sender, _
    e)
```

``` csharp
public void Application_BeginRequest(
    Object sender,
    EventArgs e
)
```

``` c++
public:
void Application_BeginRequest(
    Object^ sender, 
    EventArgs^ e
)
```

#### Parameters

  - sender  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - e  
    Type: [System.EventArgs](https://technet.microsoft.com/library/118wxtk3\(v=ax.60\))  

## See Also

#### Reference

[Global Class](global-class-microsoft-dynamics-retail-sharepoint-web-storefront.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-namespace.md)

