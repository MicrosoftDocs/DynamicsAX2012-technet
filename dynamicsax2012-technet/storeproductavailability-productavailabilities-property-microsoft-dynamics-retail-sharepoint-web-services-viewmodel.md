---
title: StoreProductAvailability.ProductAvailabilities Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ProductAvailabilities Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailability.ProductAvailabilities
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeproductavailability.productavailabilities(v=AX.60)
ms:contentKeyID: 62202854
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailability.ProductAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# ProductAvailabilities Property

Gets the item quantity

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductAvailabilities As Collection(Of StoreProductAvailabilityItem)
    Get
    Private Set
'Usage
Dim instance As StoreProductAvailability
Dim value As Collection(Of StoreProductAvailabilityItem)

value = instance.ProductAvailabilities
```

``` csharp
[DataMemberAttribute]
public Collection<StoreProductAvailabilityItem> ProductAvailabilities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<StoreProductAvailabilityItem^>^ ProductAvailabilities {
    Collection<StoreProductAvailabilityItem^>^ get ();
    private: void set (Collection<StoreProductAvailabilityItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[StoreProductAvailabilityItem](storeproductavailabilityitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailability Class](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

