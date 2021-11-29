---
title: ShoppingCart.KitComponentsColumns Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: KitComponentsColumns Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.KitComponentsColumns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.kitcomponentscolumns(v=AX.60)
ms:contentKeyID: 62203196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.KitComponentsColumns
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentsColumns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shopping cart kit columns definition in JSON format.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameKitComponents")> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionKitComponents")> _
<WebBrowsableAttribute(True)> _
Public Property KitComponentsColumns As String
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As String

value = instance.KitComponentsColumns

instance.KitComponentsColumns = value
```

``` csharp
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameKitComponents")]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionKitComponents")]
[WebBrowsableAttribute(true)]
public string KitComponentsColumns { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameKitComponents")]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionKitComponents")]
[WebBrowsableAttribute(true)]
public:
property String^ KitComponentsColumns {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

