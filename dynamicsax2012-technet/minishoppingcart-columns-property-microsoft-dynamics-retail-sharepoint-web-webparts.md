---
title: MiniShoppingCart.Columns Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.columns(v=AX.60)
ms:contentKeyID: 62203235
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the mini shopping cart columns definition in JSON format.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionColumns")> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameColumns")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<WebBrowsableAttribute(True)> _
Public Property Columns As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.Columns

instance.Columns = value
```

``` csharp
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionColumns")]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameColumns")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[WebBrowsableAttribute(true)]
public string Columns { get; set; }
```

``` c++
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionColumns")]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameColumns")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[WebBrowsableAttribute(true)]
public:
property String^ Columns {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

