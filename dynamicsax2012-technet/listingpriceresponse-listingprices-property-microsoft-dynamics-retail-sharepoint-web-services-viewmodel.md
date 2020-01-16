---
title: ListingPriceResponse.ListingPrices Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ListingPrices Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPriceResponse.ListingPrices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingpriceresponse.listingprices(v=AX.60)
ms:contentKeyID: 62202076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPriceResponse.ListingPrices
dev_langs:
- CSharp
- C++
- VB
---

# ListingPrices Property

Gets the listing prices.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingPrices As IEnumerable(Of ListingPrice)
    Get
    Set
'Usage
Dim instance As ListingPriceResponse
Dim value As IEnumerable(Of ListingPrice)

value = instance.ListingPrices

instance.ListingPrices = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ListingPrice> ListingPrices { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ListingPrice^>^ ListingPrices {
    IEnumerable<ListingPrice^>^ get ();
    void set (IEnumerable<ListingPrice^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPrice](listingprice-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ListingPriceResponse Class](listingpriceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

