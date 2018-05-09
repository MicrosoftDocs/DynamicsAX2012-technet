---
title: AddressDisplay.DisableCommandButtonRendering Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: DisableCommandButtonRendering Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay.DisableCommandButtonRendering
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.addressdisplay.disablecommandbuttonrendering(v=AX.60)
ms:contentKeyID: 62204204
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay.DisableCommandButtonRendering
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
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("AddressCustomPropertiesSettings")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("AddressWebDisplayNameDisableCommandButtonRendering")> _
<LocalizedWebDescriptionAttribute("AddressWebDescriptionDisableCommandButtonRendering")> _
<WebBrowsableAttribute(True)> _
Public Property DisableCommandButtonRendering As Boolean
    Get
    Set
'Usage
Dim instance As AddressDisplay
Dim value As Boolean

value = instance.DisableCommandButtonRendering

instance.DisableCommandButtonRendering = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("AddressCustomPropertiesSettings")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("AddressWebDisplayNameDisableCommandButtonRendering")]
[LocalizedWebDescriptionAttribute("AddressWebDescriptionDisableCommandButtonRendering")]
[WebBrowsableAttribute(true)]
public bool DisableCommandButtonRendering { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"AddressCustomPropertiesSettings")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"AddressWebDisplayNameDisableCommandButtonRendering")]
[LocalizedWebDescriptionAttribute(L"AddressWebDescriptionDisableCommandButtonRendering")]
[WebBrowsableAttribute(true)]
public:
property bool DisableCommandButtonRendering {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[AddressDisplay Class](addressdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

