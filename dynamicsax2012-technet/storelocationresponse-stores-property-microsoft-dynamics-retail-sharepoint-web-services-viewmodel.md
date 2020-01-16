---
title: StoreLocationResponse.Stores Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreLocationResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storelocationresponse.stores(v=AX.60)
ms:contentKeyID: 62203209
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreLocationResponse.Stores
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
Public Property Stores As Collection(Of StoreLocation)
    Get
    Friend Set
'Usage
Dim instance As StoreLocationResponse
Dim value As Collection(Of StoreLocation)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public Collection<StoreLocation> Stores { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<StoreLocation^>^ Stores {
    Collection<StoreLocation^>^ get ();
    internal: void set (Collection<StoreLocation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[StoreLocation](storelocation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[StoreLocationResponse Class](storelocationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

