---
title: AddressCollectionResponse.Addresses Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Addresses Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.AddressCollectionResponse.Addresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.addresscollectionresponse.addresses(v=AX.60)
ms:contentKeyID: 62204042
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.AddressCollectionResponse.Addresses
dev_langs:
- CSharp
- C++
- VB
---

# Addresses Property

Gets the collection of addresses.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Addresses As Collection(Of Address)
    Get
    Friend Set
'Usage
Dim instance As AddressCollectionResponse
Dim value As Collection(Of Address)

value = instance.Addresses
```

``` csharp
[DataMemberAttribute]
public Collection<Address> Addresses { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<Address^>^ Addresses {
    Collection<Address^>^ get ();
    internal: void set (Collection<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[AddressCollectionResponse Class](addresscollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

