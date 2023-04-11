---
title: DeliveryMethodsResponse Constructor (Collection(DeliveryMethod), Collection(ItemDeliveryMethods)) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: DeliveryMethodsResponse Constructor (Collection(DeliveryMethod), Collection(ItemDeliveryMethods))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse.#ctor(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethod},System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemDeliveryMethods})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.deliverymethodsresponse.deliverymethodsresponse(v=AX.60)
ms:contentKeyID: 62207500
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeliveryMethodsResponse Constructor (Collection(DeliveryMethod), Collection(ItemDeliveryMethods))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deliveryMethods As Collection(Of DeliveryMethod), _
    itemDeliveryMethods As Collection(Of ItemDeliveryMethods) _
)
'Usage
Dim deliveryMethods As Collection(Of DeliveryMethod)
Dim itemDeliveryMethods As Collection(Of ItemDeliveryMethods)

Dim instance As New DeliveryMethodsResponse(deliveryMethods, _
    itemDeliveryMethods)
```

``` csharp
public DeliveryMethodsResponse(
    Collection<DeliveryMethod> deliveryMethods,
    Collection<ItemDeliveryMethods> itemDeliveryMethods
)
```

``` c++
public:
DeliveryMethodsResponse(
    Collection<DeliveryMethod^>^ deliveryMethods, 
    Collection<ItemDeliveryMethods^>^ itemDeliveryMethods
)
```

#### Parameters

  - deliveryMethods  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryMethod](deliverymethod-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

<!-- end list -->

  - itemDeliveryMethods  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ItemDeliveryMethods](itemdeliverymethods-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

## See Also

#### Reference

[DeliveryMethodsResponse Class](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[DeliveryMethodsResponse Overload](deliverymethodsresponse-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

