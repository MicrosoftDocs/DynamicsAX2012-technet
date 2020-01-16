---
title: ClaimsWebPart.Render Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ClaimsWebPart)
TOCTitle: Render Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ClaimsWebPart.ClaimsWebPart.Render(System.Web.UI.HtmlTextWriter)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.claimswebpart.claimswebpart.render(v=AX.60)
ms:contentKeyID: 62202318
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ClaimsWebPart.ClaimsWebPart.Render
dev_langs:
- CSharp
- C++
- VB
---

# Render Method

Renders the control to the specified HTML writer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ClaimsWebPart](microsoft-dynamics-retail-sharepoint-web-webparts-claimswebpart-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub Render ( _
    writer As HtmlTextWriter _
)
'Usage
Dim writer As HtmlTextWriter

Me.Render(writer)
```

``` csharp
protected override void Render(
    HtmlTextWriter writer
)
```

``` c++
protected:
virtual void Render(
    HtmlTextWriter^ writer
) override
```

#### Parameters

  - writer  
    Type: [System.Web.UI.HtmlTextWriter](https://technet.microsoft.com/library/bt7b938d\(v=ax.60\))  

## See Also

#### Reference

[ClaimsWebPart Class](claimswebpart-class-microsoft-dynamics-retail-sharepoint-web-webparts-claimswebpart.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ClaimsWebPart Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-claimswebpart-namespace.md)

