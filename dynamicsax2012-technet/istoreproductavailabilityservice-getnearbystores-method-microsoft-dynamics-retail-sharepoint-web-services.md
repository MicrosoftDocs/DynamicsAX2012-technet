---
title: IStoreProductAvailabilityService.GetNearbyStores Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetNearbyStores Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetNearbyStores(System.Decimal,System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.istoreproductavailabilityservice.getnearbystores(v=AX.60)
ms:contentKeyID: 62202780
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetNearbyStores
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStores Method

Gets the nearby stores.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetNearbyStores ( _
    latitude As Decimal, _
    longitude As Decimal, _
    distance As Integer _
) As StoreLocationResponse
'Usage
Dim instance As IStoreProductAvailabilityService
Dim latitude As Decimal
Dim longitude As Decimal
Dim distance As Integer
Dim returnValue As StoreLocationResponse

returnValue = instance.GetNearbyStores(latitude, _
    longitude, distance)
```

``` csharp
[OperationContractAttribute]
StoreLocationResponse GetNearbyStores(
    decimal latitude,
    decimal longitude,
    int distance
)
```

``` c++
[OperationContractAttribute]
StoreLocationResponse^ GetNearbyStores(
    Decimal latitude, 
    Decimal longitude, 
    int distance
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - distance  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreLocationResponse](storelocationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Stores  

## See Also

#### Reference

[IStoreProductAvailabilityService Interface](istoreproductavailabilityservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

