---
title: ShoppingCart.Columns Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.Columns
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.columns(v=AX.60)
ms:contentKeyID: 62205468
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property

Gets or sets the shopping cart columns definition in JSON format.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameColumns")> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionColumns")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property Columns As String
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As String

value = instance.Columns

instance.Columns = value
```

``` csharp
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameColumns")]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionColumns")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public string Columns { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameColumns")]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionColumns")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
public:
property String^ Columns {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

