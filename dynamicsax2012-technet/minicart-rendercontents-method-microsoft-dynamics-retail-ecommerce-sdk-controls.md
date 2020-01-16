---
title: MiniCart.RenderContents Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: RenderContents Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MiniCart.RenderContents(System.Web.UI.HtmlTextWriter)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.minicart.rendercontents(v=AX.60)
ms:contentKeyID: 65316002
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MiniCart.RenderContents
dev_langs:
- CSharp
- C++
- VB
---

# RenderContents Method

This member overrides [WebControl.RenderContents(HtmlTextWriter)](https://technet.microsoft.com/library/sb0s70ds\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub RenderContents ( _
    writer As HtmlTextWriter _
)
'Usage
Dim writer As HtmlTextWriter

Me.RenderContents(writer)
```

``` csharp
protected override void RenderContents(
    HtmlTextWriter writer
)
```

``` c++
protected:
virtual void RenderContents(
    HtmlTextWriter^ writer
) override
```

#### Parameters

  - writer  
    Type: [System.Web.UI.HtmlTextWriter](https://technet.microsoft.com/library/bt7b938d\(v=ax.60\))  

## See Also

#### Reference

[MiniCart Class](minicart-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

