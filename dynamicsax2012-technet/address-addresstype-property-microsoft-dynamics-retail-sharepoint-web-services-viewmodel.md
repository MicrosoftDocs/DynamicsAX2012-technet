---
title: Address.AddressType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AddressType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address.AddressType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.address.addresstype(v=AX.60)
ms:contentKeyID: 62206648
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address.AddressType
dev_langs:
- CSharp
- C++
- VB
---

# AddressType Property

Gets or sets the AddressType for this Address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressType As AddressType
    Get
    Set
'Usage
Dim instance As Address
Dim value As AddressType

value = instance.AddressType

instance.AddressType = value
```

``` csharp
[DataMemberAttribute]
public AddressType AddressType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property AddressType AddressType {
    AddressType get ();
    void set (AddressType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.AddressType](addresstype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [AddressType](addresstype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

