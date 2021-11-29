---
title: CustomerResponse.Customer Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Customer Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse.Customer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.customerresponse.customer(v=AX.60)
ms:contentKeyID: 62203261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customer As Customer
    Get
    Set
'Usage
Dim instance As CustomerResponse
Dim value As Customer

value = instance.Customer

instance.Customer = value
```

``` csharp
[DataMemberAttribute]
public Customer Customer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ Customer {
    Customer^ get ();
    void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[CustomerResponse Class](customerresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

