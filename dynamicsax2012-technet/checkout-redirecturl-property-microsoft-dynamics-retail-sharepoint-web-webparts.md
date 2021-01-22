---
title: Checkout.RedirectUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RedirectUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.RedirectUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.checkout.redirecturl(v=AX.60)
ms:contentKeyID: 62203353
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.RedirectUrl
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUrl Property

Gets or sets the shopping cart page to redirect to.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<LocalizedWebDescriptionAttribute("CheckoutWebDescriptionRedirectUrl")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedCategoryAttribute("CheckoutCustomPropertiesSettings")> _
<LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameRedirectUrl")> _
Public Property RedirectUrl As String
    Get
    Set
'Usage
Dim instance As Checkout
Dim value As String

value = instance.RedirectUrl

instance.RedirectUrl = value
```

``` csharp
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute("CheckoutWebDescriptionRedirectUrl")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedCategoryAttribute("CheckoutCustomPropertiesSettings")]
[LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameRedirectUrl")]
public string RedirectUrl { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute(L"CheckoutWebDescriptionRedirectUrl")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedCategoryAttribute(L"CheckoutCustomPropertiesSettings")]
[LocalizedWebDisplayNameAttribute(L"CheckoutWebDisplayNameRedirectUrl")]
public:
property String^ RedirectUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Checkout Class](checkout-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

