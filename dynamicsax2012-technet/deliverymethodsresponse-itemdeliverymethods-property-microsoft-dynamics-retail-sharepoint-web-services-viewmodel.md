---
title: DeliveryMethodsResponse.ItemDeliveryMethods Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemDeliveryMethods Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse.ItemDeliveryMethods
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.deliverymethodsresponse.itemdeliverymethods(v=AX.60)
ms:contentKeyID: 62204500
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse.ItemDeliveryMethods
dev_langs:
- CSharp
- C++
- VB
---

# ItemDeliveryMethods Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery methods per item.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemDeliveryMethods As Collection(Of ItemDeliveryMethods)
    Get
    Private Set
'Usage
Dim instance As DeliveryMethodsResponse
Dim value As Collection(Of ItemDeliveryMethods)

value = instance.ItemDeliveryMethods
```

``` csharp
[DataMemberAttribute]
public Collection<ItemDeliveryMethods> ItemDeliveryMethods { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ItemDeliveryMethods^>^ ItemDeliveryMethods {
    Collection<ItemDeliveryMethods^>^ get ();
    private: void set (Collection<ItemDeliveryMethods^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ItemDeliveryMethods](itemdeliverymethods-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[DeliveryMethodsResponse Class](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

