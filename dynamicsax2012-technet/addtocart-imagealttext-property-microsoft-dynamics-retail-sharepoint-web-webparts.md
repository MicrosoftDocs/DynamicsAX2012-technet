---
title: AddToCart.ImageAltText Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ImageAltText Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ImageAltText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.addtocart.imagealttext(v=AX.60)
ms:contentKeyID: 62204035
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ImageAltText
dev_langs:
- CSharp
- C++
- VB
---

# ImageAltText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the alternative text to display for the AddToCart image.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("AddToCartCustomPropertiesImage")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameImageAltText")> _
<LocalizedWebDescriptionAttribute("AddToCartWebDescriptionImageAltText")> _
Public Property ImageAltText As String
    Get
    Set
'Usage
Dim instance As AddToCart
Dim value As String

value = instance.ImageAltText

instance.ImageAltText = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("AddToCartCustomPropertiesImage")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameImageAltText")]
[LocalizedWebDescriptionAttribute("AddToCartWebDescriptionImageAltText")]
public string ImageAltText { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"AddToCartCustomPropertiesImage")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"AddToCartWebDisplayNameImageAltText")]
[LocalizedWebDescriptionAttribute(L"AddToCartWebDescriptionImageAltText")]
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

[AddToCart Class](addtocart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

