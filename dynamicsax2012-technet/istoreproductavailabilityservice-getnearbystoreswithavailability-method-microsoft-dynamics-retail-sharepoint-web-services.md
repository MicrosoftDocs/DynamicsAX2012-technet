---
title: IStoreProductAvailabilityService.GetNearbyStoresWithAvailability Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetNearbyStoresWithAvailability Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetNearbyStoresWithAvailability(System.Decimal,System.Decimal,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.istoreproductavailabilityservice.getnearbystoreswithavailability(v=AX.60)
ms:contentKeyID: 62203302
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetNearbyStoresWithAvailability
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStoresWithAvailability Method

Gets the nearby stores with availability.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetNearbyStoresWithAvailability ( _
    latitude As Decimal, _
    longitude As Decimal, _
    items As IEnumerable(Of ShoppingCartItem) _
) As StoreProductAvailabilityResponse
'Usage
Dim instance As IStoreProductAvailabilityService
Dim latitude As Decimal
Dim longitude As Decimal
Dim items As IEnumerable(Of ShoppingCartItem)
Dim returnValue As StoreProductAvailabilityResponse

returnValue = instance.GetNearbyStoresWithAvailability(latitude, _
    longitude, items)
```

``` csharp
[OperationContractAttribute]
StoreProductAvailabilityResponse GetNearbyStoresWithAvailability(
    decimal latitude,
    decimal longitude,
    IEnumerable<ShoppingCartItem> items
)
```

``` c++
[OperationContractAttribute]
StoreProductAvailabilityResponse^ GetNearbyStoresWithAvailability(
    Decimal latitude, 
    Decimal longitude, 
    IEnumerable<ShoppingCartItem^>^ items
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ShoppingCartItem](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityResponse](storeproductavailabilityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Stores with product availability.  

## See Also

#### Reference

[IStoreProductAvailabilityService Interface](istoreproductavailabilityservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

