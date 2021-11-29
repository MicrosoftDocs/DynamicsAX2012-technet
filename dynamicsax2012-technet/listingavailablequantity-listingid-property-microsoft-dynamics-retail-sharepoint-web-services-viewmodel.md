---
title: ListingAvailableQuantity.ListingId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ListingId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.ListingId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingavailablequantity.listingid(v=AX.60)
ms:contentKeyID: 62207037
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.ListingId
dev_langs:
- CSharp
- C++
- VB
---

# ListingId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the listing identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingId As Long
    Get
    Set
'Usage
Dim instance As ListingAvailableQuantity
Dim value As Long

value = instance.ListingId

instance.ListingId = value
```

``` csharp
[DataMemberAttribute]
public long ListingId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ListingId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ListingAvailableQuantity Class](listingavailablequantity-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

