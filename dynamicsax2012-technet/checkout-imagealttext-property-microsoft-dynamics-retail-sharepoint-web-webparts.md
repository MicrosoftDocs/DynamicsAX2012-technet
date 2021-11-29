---
title: Checkout.ImageAltText Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ImageAltText Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.ImageAltText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.checkout.imagealttext(v=AX.60)
ms:contentKeyID: 62207012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout.ImageAltText
dev_langs:
- CSharp
- C++
- VB
---

# ImageAltText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the alternative text to display for the Checkout image.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameImageAltText")> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDescriptionAttribute("CheckoutWebDescriptionImageAltText")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("CheckoutCustomPropertiesImage")> _
<WebPartStorageAttribute(Storage.Shared)> _
Public Property ImageAltText As String
    Get
    Set
'Usage
Dim instance As Checkout
Dim value As String

value = instance.ImageAltText

instance.ImageAltText = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("CheckoutWebDisplayNameImageAltText")]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute("CheckoutWebDescriptionImageAltText")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("CheckoutCustomPropertiesImage")]
[WebPartStorageAttribute(Storage.Shared)]
public string ImageAltText { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"CheckoutWebDisplayNameImageAltText")]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute(L"CheckoutWebDescriptionImageAltText")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"CheckoutCustomPropertiesImage")]
[WebPartStorageAttribute(Storage::Shared)]
public:
property String^ ImageAltText {
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

