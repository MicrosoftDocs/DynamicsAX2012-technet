---
title: Address.DisableCommandButtonRendering Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: DisableCommandButtonRendering Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address.DisableCommandButtonRendering
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.address.disablecommandbuttonrendering(v=AX.60)
ms:contentKeyID: 62205632
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address.DisableCommandButtonRendering
dev_langs:
- CSharp
- C++
- VB
---

# DisableCommandButtonRendering Property

Gets or sets whether to disable the template block and output container.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedCategoryAttribute("AddressCustomPropertiesSettings")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDescriptionAttribute("AddressWebDescriptionDisableCommandButtonRendering")> _
<LocalizedWebDisplayNameAttribute("AddressWebDisplayNameDisableCommandButtonRendering")> _
Public Property DisableCommandButtonRendering As Boolean
    Get
    Set
'Usage
Dim instance As Address
Dim value As Boolean

value = instance.DisableCommandButtonRendering

instance.DisableCommandButtonRendering = value
```

``` csharp
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedCategoryAttribute("AddressCustomPropertiesSettings")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute("AddressWebDescriptionDisableCommandButtonRendering")]
[LocalizedWebDisplayNameAttribute("AddressWebDisplayNameDisableCommandButtonRendering")]
public bool DisableCommandButtonRendering { get; set; }
```

``` c++
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedCategoryAttribute(L"AddressCustomPropertiesSettings")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute(L"AddressWebDescriptionDisableCommandButtonRendering")]
[LocalizedWebDisplayNameAttribute(L"AddressWebDisplayNameDisableCommandButtonRendering")]
public:
property bool DisableCommandButtonRendering {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

