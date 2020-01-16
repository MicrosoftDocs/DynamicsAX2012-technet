---
title: ListingAvailableQuantity.AvailableQuantity Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AvailableQuantity Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.AvailableQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingavailablequantity.availablequantity(v=AX.60)
ms:contentKeyID: 62205992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.AvailableQuantity
dev_langs:
- CSharp
- C++
- VB
---

# AvailableQuantity Property

Gets or sets the available quantity.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AvailableQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ListingAvailableQuantity
Dim value As Decimal

value = instance.AvailableQuantity

instance.AvailableQuantity = value
```

``` csharp
[DataMemberAttribute]
public decimal AvailableQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AvailableQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ListingAvailableQuantity Class](listingavailablequantity-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

