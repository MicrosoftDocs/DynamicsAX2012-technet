---
title: StoreProductAvailabilityService.GetNearbyStores Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetNearbyStores Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetNearbyStores(System.Decimal,System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.storeproductavailabilityservice.getnearbystores(v=AX.60)
ms:contentKeyID: 62207369
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetNearbyStores
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the nearby stores.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetNearbyStores ( _
    latitude As Decimal, _
    longitude As Decimal, _
    distance As Integer _
) As StoreLocationResponse
'Usage
Dim instance As StoreProductAvailabilityService
Dim latitude As Decimal
Dim longitude As Decimal
Dim distance As Integer
Dim returnValue As StoreLocationResponse

returnValue = instance.GetNearbyStores(latitude, _
    longitude, distance)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public StoreLocationResponse GetNearbyStores(
    decimal latitude,
    decimal longitude,
    int distance
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual StoreLocationResponse^ GetNearbyStores(
    Decimal latitude, 
    Decimal longitude, 
    int distance
) sealed
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - distance  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreLocationResponse](storelocationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Stores.  

#### Implements

[IStoreProductAvailabilityService.GetNearbyStores(Decimal, Decimal, Int32)](istoreproductavailabilityservice-getnearbystores-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityService Class](storeproductavailabilityservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

