---
title: Address.StreetNumber Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: StreetNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.StreetNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.address.streetnumber(v=AX.60)
ms:contentKeyID: 62204071
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.StreetNumber
dev_langs:
- CSharp
- C++
- VB
---

# StreetNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the StreetNumber.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property StreetNumber As HtmlInputText
    Get
    Private Set
'Usage
Dim instance As Address
Dim value As HtmlInputText

value = instance.StreetNumber
```

``` csharp
public HtmlInputText StreetNumber { get; private set; }
```

``` c++
public:
property HtmlInputText^ StreetNumber {
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

