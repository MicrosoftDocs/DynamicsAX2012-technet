---
title: HtmlRadioButtons.AddRadioButton Method (HtmlInputRadioButton, HtmlLabel, HtmlControl) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddRadioButton Method (HtmlInputRadioButton, HtmlLabel, HtmlControl)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlRadioButtons.AddRadioButton(System.Web.UI.HtmlControls.HtmlInputRadioButton,Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel,System.Web.UI.HtmlControls.HtmlControl)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlradiobuttons.addradiobutton(v=AX.60)
ms:contentKeyID: 62206114
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddRadioButton Method (HtmlInputRadioButton, HtmlLabel, HtmlControl)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds a radio button to the group with the radio button control and associated label.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Sub AddRadioButton ( _
    radioButton As HtmlInputRadioButton, _
    radioButtonLabel As HtmlLabel, _
    container As HtmlControl _
)
'Usage
Dim instance As HtmlRadioButtons
Dim radioButton As HtmlInputRadioButton
Dim radioButtonLabel As HtmlLabel
Dim container As HtmlControl

instance.AddRadioButton(radioButton, _
    radioButtonLabel, container)
```

``` csharp
public void AddRadioButton(
    HtmlInputRadioButton radioButton,
    HtmlLabel radioButtonLabel,
    HtmlControl container
)
```

``` c++
public:
void AddRadioButton(
    HtmlInputRadioButton^ radioButton, 
    HtmlLabel^ radioButtonLabel, 
    HtmlControl^ container
)
```

#### Parameters

  - radioButton  
    Type: [System.Web.UI.HtmlControls.HtmlInputRadioButton](https://technet.microsoft.com/library/w2yk46b2\(v=ax.60\))  

<!-- end list -->

  - radioButtonLabel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel](htmllabel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  

<!-- end list -->

  - container  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

## See Also

#### Reference

[HtmlRadioButtons Class](htmlradiobuttons-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[AddRadioButton Overload](htmlradiobuttons-addradiobutton-method-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

