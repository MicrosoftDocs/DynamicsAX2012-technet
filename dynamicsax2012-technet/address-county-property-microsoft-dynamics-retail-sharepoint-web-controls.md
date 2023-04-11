---
title: Address.County Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: County Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.County
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.address.county(v=AX.60)
ms:contentKeyID: 62203563
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.County
dev_langs:
- CSharp
- C++
- VB
---

# County Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets County.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property County As HtmlInputText
    Get
    Private Set
'Usage
Dim instance As Address
Dim value As HtmlInputText

value = instance.County
```

``` csharp
public HtmlInputText County { get; private set; }
```

``` c++
public:
property HtmlInputText^ County {
    HtmlInputText^ get ();
    private: void set (HtmlInputText^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlInputText](https://technet.microsoft.com/library/hx8x1zw4\(v=ax.60\))  
Returns [HtmlInputText](https://technet.microsoft.com/library/hx8x1zw4\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

