---
title: AddToCart.ListingIdSelector Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ListingIdSelector Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ListingIdSelector
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.addtocart.listingidselector(v=AX.60)
ms:contentKeyID: 62203907
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.ListingIdSelector
dev_langs:
- CSharp
- C++
- VB
---

# ListingIdSelector Property

Gets or sets the jQuery selector to use to obtain the listingId from the page.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("AddToCartCustomPropertiesSettings")> _
<WebPartStorageAttribute(Storage.Shared)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameListingIdSelector")> _
<LocalizedWebDescriptionAttribute("AddToCartWebDescriptionListingIdSelector")> _
<WebBrowsableAttribute(True)> _
Public Property ListingIdSelector As String
    Get
    Set
'Usage
Dim instance As AddToCart
Dim value As String

value = instance.ListingIdSelector

instance.ListingIdSelector = value
```

``` csharp
[LocalizedCategoryAttribute("AddToCartCustomPropertiesSettings")]
[WebPartStorageAttribute(Storage.Shared)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameListingIdSelector")]
[LocalizedWebDescriptionAttribute("AddToCartWebDescriptionListingIdSelector")]
[WebBrowsableAttribute(true)]
public string ListingIdSelector { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"AddToCartCustomPropertiesSettings")]
[WebPartStorageAttribute(Storage::Shared)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDisplayNameAttribute(L"AddToCartWebDisplayNameListingIdSelector")]
[LocalizedWebDescriptionAttribute(L"AddToCartWebDescriptionListingIdSelector")]
[WebBrowsableAttribute(true)]
public:
property String^ ListingIdSelector {
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

