---
title: ItemDeliveryMethods Constructor (String, Collection(DeliveryMethod)) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemDeliveryMethods Constructor (String, Collection(DeliveryMethod))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemDeliveryMethods.#ctor(System.String,System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethod})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.itemdeliverymethods.itemdeliverymethods(v=AX.60)
ms:contentKeyID: 62207364
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemDeliveryMethods Constructor (String, Collection(DeliveryMethod))

Initializes a new instance of the [ItemDeliveryMethods](itemdeliverymethods-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lineId As String, _
    deliveryMethods As Collection(Of DeliveryMethod) _
)
'Usage
Dim lineId As String
Dim deliveryMethods As Collection(Of DeliveryMethod)

Dim instance As New ItemDeliveryMethods(lineId, _
    deliveryMethods)
```

``` csharp
public ItemDeliveryMethods(
    string lineId,
    Collection<DeliveryMethod> deliveryMethods
)
```

``` c++
public:
ItemDeliveryMethods(
    String^ lineId, 
    Collection<DeliveryMethod^>^ deliveryMethods
)
```

#### Parameters

  - lineId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deliveryMethods  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DeliveryMethod](deliverymethod-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

## See Also

#### Reference

[ItemDeliveryMethods Class](itemdeliverymethods-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[ItemDeliveryMethods Overload](itemdeliverymethods-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

