---
title: ListingAvailableQuantityResponse.ListingAvailableQuantities Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ListingAvailableQuantities Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantityResponse.ListingAvailableQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingavailablequantityresponse.listingavailablequantities(v=AX.60)
ms:contentKeyID: 62204291
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantityResponse.ListingAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ListingAvailableQuantities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantities available for listings.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingAvailableQuantities As IEnumerable(Of ListingAvailableQuantity)
    Get
    Set
'Usage
Dim instance As ListingAvailableQuantityResponse
Dim value As IEnumerable(Of ListingAvailableQuantity)

value = instance.ListingAvailableQuantities

instance.ListingAvailableQuantities = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ListingAvailableQuantity> ListingAvailableQuantities { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ListingAvailableQuantity^>^ ListingAvailableQuantities {
    IEnumerable<ListingAvailableQuantity^>^ get ();
    void set (IEnumerable<ListingAvailableQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingAvailableQuantity](listingavailablequantity-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ListingAvailableQuantityResponse Class](listingavailablequantityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

