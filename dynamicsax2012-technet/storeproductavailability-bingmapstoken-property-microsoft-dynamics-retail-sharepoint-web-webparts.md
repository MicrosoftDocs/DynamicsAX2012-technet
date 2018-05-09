---
title: StoreProductAvailability.BingMapsToken Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: BingMapsToken Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability.BingMapsToken
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.storeproductavailability.bingmapstoken(v=AX.60)
ms:contentKeyID: 62203272
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability.BingMapsToken
dev_langs:
- CSharp
- C++
- VB
---

# BingMapsToken Property

Gets or sets Bing map authentication token.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<WebPartStorageAttribute(Storage.Shared)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebDescriptionAttribute("Authentication token to be used with Bing maps.")> _
<WebDisplayNameAttribute("Bing maps token")> _
Public Property BingMapsToken As String
    Get
    Set
'Usage
Dim instance As StoreProductAvailability
Dim value As String

value = instance.BingMapsToken

instance.BingMapsToken = value
```

``` csharp
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage.Shared)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebDescriptionAttribute("Authentication token to be used with Bing maps.")]
[WebDisplayNameAttribute("Bing maps token")]
public string BingMapsToken { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage::Shared)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebDescriptionAttribute(L"Authentication token to be used with Bing maps.")]
[WebDisplayNameAttribute(L"Bing maps token")]
public:
property String^ BingMapsToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailability Class](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

