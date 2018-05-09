---
title: SubmitOrder.ConfirmationPage Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: ConfirmationPage Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.SubmitOrder.ConfirmationPage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.submitorder.confirmationpage(v=AX.60)
ms:contentKeyID: 62204894
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.SubmitOrder.ConfirmationPage
dev_langs:
- CSharp
- C++
- VB
---

# ConfirmationPage Property

Gets or sets the confirmation page to redirect to after adding an item to the cart. Empty Url means no redirect.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property ConfirmationPage As String
    Get
    Set
'Usage
Dim instance As SubmitOrder
Dim value As String

value = instance.ConfirmationPage

instance.ConfirmationPage = value
```

``` csharp
public string ConfirmationPage { get; set; }
```

``` c++
public:
property String^ ConfirmationPage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SubmitOrder Class](submitorder-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

