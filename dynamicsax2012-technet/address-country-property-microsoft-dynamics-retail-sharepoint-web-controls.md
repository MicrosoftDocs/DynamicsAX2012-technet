---
title: Address.Country Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: Country Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.Country
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.address.country(v=AX.60)
ms:contentKeyID: 62202936
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.Address.Country
dev_langs:
- CSharp
- C++
- VB
---

# Country Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Country.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property Country As HtmlSelect
    Get
    Private Set
'Usage
Dim instance As Address
Dim value As HtmlSelect

value = instance.Country
```

``` csharp
public HtmlSelect Country { get; private set; }
```

``` c++
public:
property HtmlSelect^ Country {
    HtmlSelect^ get ();
    private: void set (HtmlSelect^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlSelect](https://technet.microsoft.com/library/xf11z4ad\(v=ax.60\))  
Returns [HtmlSelect](https://technet.microsoft.com/library/xf11z4ad\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

