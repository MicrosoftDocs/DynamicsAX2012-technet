---
title: AddToCart.ImageUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ImageUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ImageUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.addtocart.imageurl(v=AX.60)
ms:contentKeyID: 62203807
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ImageUrl
dev_langs:
- CSharp
- C++
- VB
---

# ImageUrl Property

Gets or sets the URL of the Image to render as the AddToCart button.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameImageUrl")> _
<LocalizedWebDescriptionAttribute("AddToCartWebDescriptionImageUrl")> _
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("AddToCartCustomPropertiesImage")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property ImageUrl As String
    Get
    Set
'Usage
Dim instance As AddToCart
Dim value As String

value = instance.ImageUrl

instance.ImageUrl = value
```

``` csharp
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameImageUrl")]
[LocalizedWebDescriptionAttribute("AddToCartWebDescriptionImageUrl")]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("AddToCartCustomPropertiesImage")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public string ImageUrl { get; set; }
```

``` c++
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"AddToCartWebDisplayNameImageUrl")]
[LocalizedWebDescriptionAttribute(L"AddToCartWebDescriptionImageUrl")]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"AddToCartCustomPropertiesImage")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
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

[AddToCart Class](addtocart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

