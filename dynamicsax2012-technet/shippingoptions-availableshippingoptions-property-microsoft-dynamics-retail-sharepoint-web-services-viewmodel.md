---
title: ShippingOptions.AvailableShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AvailableShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions.AvailableShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shippingoptions.availableshippingoptions(v=AX.60)
ms:contentKeyID: 62204649
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions.AvailableShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# AvailableShippingOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the availabe shipping options to choose from such as pick up from store, ship to saved addresses, etc.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AvailableShippingOptions As Collection(Of ShippingOption)
    Get
    Private Set
'Usage
Dim instance As ShippingOptions
Dim value As Collection(Of ShippingOption)

value = instance.AvailableShippingOptions
```

``` csharp
[DataMemberAttribute]
public Collection<ShippingOption> AvailableShippingOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShippingOption^>^ AvailableShippingOptions {
    Collection<ShippingOption^>^ get ();
    private: void set (Collection<ShippingOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ShippingOption](shippingoption-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ShippingOptions Class](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

