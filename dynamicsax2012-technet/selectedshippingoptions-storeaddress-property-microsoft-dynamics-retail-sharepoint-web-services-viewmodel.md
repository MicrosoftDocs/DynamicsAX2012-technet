---
title: SelectedShippingOptions.StoreAddress Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: StoreAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.StoreAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.storeaddress(v=AX.60)
ms:contentKeyID: 62202827
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.StoreAddress
dev_langs:
- CSharp
- C++
- VB
---

# StoreAddress Property

Gets or sets the store address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreAddress As StoreProductAvailability
    Get
    Private Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As StoreProductAvailability

value = instance.StoreAddress
```

``` csharp
[DataMemberAttribute]
public StoreProductAvailability StoreAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property StoreProductAvailability^ StoreAddress {
    StoreProductAvailability^ get ();
    private: void set (StoreProductAvailability^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## Remarks

This is supposed to be set with in-store pickup.

## See Also

#### Reference

[SelectedShippingOptions Class](selectedshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

