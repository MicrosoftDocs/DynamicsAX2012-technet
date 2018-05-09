---
title: Listing.KitComponentDetails Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitComponentDetails Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.KitComponentDetails
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listing.kitcomponentdetails(v=AX.60)
ms:contentKeyID: 62203024
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.KitComponentDetails
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentDetails Property

Gets or sets the details of the kit components if the present listing is that of a kit.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentDetails As Collection(Of KitComponentInfo)
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Collection(Of KitComponentInfo)

value = instance.KitComponentDetails

instance.KitComponentDetails = value
```

``` csharp
[DataMemberAttribute]
public Collection<KitComponentInfo> KitComponentDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<KitComponentInfo^>^ KitComponentDetails {
    Collection<KitComponentInfo^>^ get ();
    void set (Collection<KitComponentInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[KitComponentInfo](kitcomponentinfo-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

