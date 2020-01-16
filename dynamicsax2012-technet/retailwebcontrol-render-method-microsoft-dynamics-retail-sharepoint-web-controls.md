---
title: RetailWebControl.Render Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: Render Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.RetailWebControl.Render(System.Web.UI.HtmlTextWriter)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.retailwebcontrol.render(v=AX.60)
ms:contentKeyID: 62202391
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.RetailWebControl.Render
dev_langs:
- CSharp
- C++
- VB
---

# Render Method

Renders the basic web control wrapper with the default container and an animation div.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

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

[RetailWebControl Class](retailwebcontrol-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

