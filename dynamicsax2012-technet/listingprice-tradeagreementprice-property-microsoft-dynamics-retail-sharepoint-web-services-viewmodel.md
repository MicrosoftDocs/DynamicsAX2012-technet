---
title: ListingPrice.TradeAgreementPrice Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: TradeAgreementPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.TradeAgreementPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingprice.tradeagreementprice(v=AX.60)
ms:contentKeyID: 62205926
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.TradeAgreementPrice
dev_langs:
- CSharp
- C++
- VB
---

# TradeAgreementPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the trade agreement price for the listing.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TradeAgreementPrice As String
    Get
    Set
'Usage
Dim instance As ListingPrice
Dim value As String

value = instance.TradeAgreementPrice

instance.TradeAgreementPrice = value
```

``` csharp
[DataMemberAttribute]
public string TradeAgreementPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TradeAgreementPrice {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

If no trade agreements found, this is the BasePrice.

## See Also

#### Reference

[ListingPrice Class](listingprice-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

