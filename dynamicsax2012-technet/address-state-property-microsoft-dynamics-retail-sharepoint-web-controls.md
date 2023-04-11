---
title: Address.State Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: State Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.State
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.address.state(v=AX.60)
ms:contentKeyID: 62202294
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.State
dev_langs:
- CSharp
- C++
- VB
---

# State Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the State.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property State As HtmlInputText
    Get
    Private Set
'Usage
Dim instance As Address
Dim value As HtmlInputText

value = instance.State
```

``` csharp
public HtmlInputText State { get; private set; }
```

``` c++
public:
property HtmlInputText^ State {
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

