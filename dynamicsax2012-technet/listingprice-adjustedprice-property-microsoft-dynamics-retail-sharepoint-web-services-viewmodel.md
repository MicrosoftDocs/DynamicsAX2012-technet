---
title: ListingPrice.AdjustedPrice Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AdjustedPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.AdjustedPrice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingprice.adjustedprice(v=AX.60)
ms:contentKeyID: 62202379
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.AdjustedPrice
dev_langs:
- CSharp
- C++
- VB
---

# AdjustedPrice Property

Gets or sets the adjusted price for the listing.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdjustedPrice As String
    Get
    Set
'Usage
Dim instance As ListingPrice
Dim value As String

value = instance.AdjustedPrice

instance.AdjustedPrice = value
```

``` csharp
[DataMemberAttribute]
public string AdjustedPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AdjustedPrice {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This is the best of the TradeAgreementPrice and retail price adjustments.

## See Also

#### Reference

[ListingPrice Class](listingprice-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

