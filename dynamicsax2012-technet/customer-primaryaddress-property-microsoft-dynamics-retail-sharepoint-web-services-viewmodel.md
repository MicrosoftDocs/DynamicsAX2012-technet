---
title: Customer.PrimaryAddress Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PrimaryAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer.PrimaryAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.customer.primaryaddress(v=AX.60)
ms:contentKeyID: 62207494
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer.PrimaryAddress
dev_langs:
- CSharp
- C++
- VB
---

# PrimaryAddress Property

Gets or sets the customer primary Address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PrimaryAddress As Address
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Address

value = instance.PrimaryAddress

instance.PrimaryAddress = value
```

``` csharp
[DataMemberAttribute]
public Address PrimaryAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ PrimaryAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

