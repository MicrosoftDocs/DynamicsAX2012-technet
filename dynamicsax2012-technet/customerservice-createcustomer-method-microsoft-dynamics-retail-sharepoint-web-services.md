---
title: CustomerService.CreateCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.CreateCustomer(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.createcustomer(v=AX.60)
ms:contentKeyID: 62207514
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.CreateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function CreateCustomer ( _
    customer As Customer _
) As CustomerResponse
'Usage
Dim instance As CustomerService
Dim customer As Customer
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomer(customer)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public CustomerResponse CreateCustomer(
    Customer customer
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual CustomerResponse^ CreateCustomer(
    Customer^ customer
) sealed
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A customer response.  

#### Implements

[ICustomerService.CreateCustomer(Customer)](icustomerservice-createcustomer-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

