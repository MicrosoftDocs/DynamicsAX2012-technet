---
title: StoreProductAvailabilityResponse.Stores Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeproductavailabilityresponse.stores(v=AX.60)
ms:contentKeyID: 62206972
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property

Enumerable list of stores.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As Collection(Of StoreProductAvailability)
    Get
    Friend Set
'Usage
Dim instance As StoreProductAvailabilityResponse
Dim value As Collection(Of StoreProductAvailability)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public Collection<StoreProductAvailability> Stores { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<StoreProductAvailability^>^ Stores {
    Collection<StoreProductAvailability^>^ get ();
    internal: void set (Collection<StoreProductAvailability^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailabilityResponse Class](storeproductavailabilityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

