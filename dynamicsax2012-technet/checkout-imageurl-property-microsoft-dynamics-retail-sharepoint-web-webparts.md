---
title: Checkout.ImageUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ImageUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.ImageUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.checkout.imageurl(v=AX.60)
ms:contentKeyID: 62204052
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.ImageUrl
dev_langs:
- CSharp
- C++
- VB
---

# ImageUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the URL of the Image to render as the Checkout button.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameImageUrl")> _
<WebPartStorageAttribute(Storage.Shared)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDescriptionAttribute("CheckoutWebDescriptionImageUrl")> _
<LocalizedCategoryAttribute("CheckoutCustomPropertiesImage")> _
<WebBrowsableAttribute(True)> _
Public Property ImageUrl As String
    Get
    Set
'Usage
Dim instance As Checkout
Dim value As String

value = instance.ImageUrl

instance.ImageUrl = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameImageUrl")]
[WebPartStorageAttribute(Storage.Shared)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDescriptionAttribute("CheckoutWebDescriptionImageUrl")]
[LocalizedCategoryAttribute("CheckoutCustomPropertiesImage")]
[WebBrowsableAttribute(true)]
public string ImageUrl { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"CheckoutWebDisplayNameImageUrl")]
[WebPartStorageAttribute(Storage::Shared)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDescriptionAttribute(L"CheckoutWebDescriptionImageUrl")]
[LocalizedCategoryAttribute(L"CheckoutCustomPropertiesImage")]
[WebBrowsableAttribute(true)]
public:
property String^ ImageUrl {
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

