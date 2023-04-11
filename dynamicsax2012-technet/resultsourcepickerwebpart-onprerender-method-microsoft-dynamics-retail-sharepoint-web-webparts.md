---
title: ResultSourcePickerWebPart.OnPreRender Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: OnPreRender Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultSourcePickerWebPart.OnPreRender(System.EventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resultsourcepickerwebpart.onprerender(v=AX.60)
ms:contentKeyID: 62205216
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultSourcePickerWebPart.OnPreRender
dev_langs:
- CSharp
- C++
- VB
---

# OnPreRender Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Raises the [PreRender](https://technet.microsoft.com/library/768a7bzf\(v=ax.60\)) event.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub OnPreRender ( _
    e As EventArgs _
)
'Usage
Dim e As EventArgs

Me.OnPreRender(e)
```

``` csharp
protected override void OnPreRender(
    EventArgs e
)
```

``` c++
protected:
virtual void OnPreRender(
    EventArgs^ e
) override
```

#### Parameters

  - e  
    Type: [System.EventArgs](https://technet.microsoft.com/library/118wxtk3\(v=ax.60\))  

## See Also

#### Reference

[ResultSourcePickerWebPart Class](resultsourcepickerwebpart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

