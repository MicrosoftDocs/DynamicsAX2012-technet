---
title: PromotionCode.Page_Load Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Page_Load Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.PromotionCode.Page_Load(System.Object,System.EventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.promotioncode.page_load(v=AX.60)
ms:contentKeyID: 62205623
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.PromotionCode.Page_Load
dev_langs:
- CSharp
- C++
- VB
---

# Page\_Load Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the Load event of the Page control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Sub Page_Load ( _
    sender As Object, _
    e As EventArgs _
)
'Usage
Dim sender As Object
Dim e As EventArgs

Me.Page_Load(sender, e)
```

``` csharp
protected void Page_Load(
    Object sender,
    EventArgs e
)
```

``` c++
protected:
void Page_Load(
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

[PromotionCode Class](promotioncode-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

