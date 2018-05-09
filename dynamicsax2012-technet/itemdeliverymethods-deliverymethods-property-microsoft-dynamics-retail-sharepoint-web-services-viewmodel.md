---
title: ItemDeliveryMethods.DeliveryMethods Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: DeliveryMethods Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemDeliveryMethods.DeliveryMethods
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.itemdeliverymethods.deliverymethods(v=AX.60)
ms:contentKeyID: 62202887
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemDeliveryMethods.DeliveryMethods
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMethods Property

Gets or sets the delivery methods.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryMethods As Collection(Of DeliveryMethod)
    Get
    Private Set
'Usage
Dim instance As ItemDeliveryMethods
Dim value As Collection(Of DeliveryMethod)

value = instance.DeliveryMethods
```

``` csharp
[DataMemberAttribute]
public Collection<DeliveryMethod> DeliveryMethods { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<DeliveryMethod^>^ DeliveryMethods {
    Collection<DeliveryMethod^>^ get ();
    private: void set (Collection<DeliveryMethod^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DeliveryMethod](deliverymethod-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ItemDeliveryMethods Class](itemdeliverymethods-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

