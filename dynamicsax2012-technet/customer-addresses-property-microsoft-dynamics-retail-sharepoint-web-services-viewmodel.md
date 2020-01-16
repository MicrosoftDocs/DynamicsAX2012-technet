---
title: Customer.Addresses Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Addresses Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer.Addresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.customer.addresses(v=AX.60)
ms:contentKeyID: 62205409
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer.Addresses
dev_langs:
- CSharp
- C++
- VB
---

# Addresses Property

Gets or sets the customer Addresses.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Addresses As IEnumerable(Of Address)
    Get
    Set
'Usage
Dim instance As Customer
Dim value As IEnumerable(Of Address)

value = instance.Addresses

instance.Addresses = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<Address> Addresses { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<Address^>^ Addresses {
    IEnumerable<Address^>^ get ();
    void set (IEnumerable<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

