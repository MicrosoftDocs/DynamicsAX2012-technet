---
title: CustomerService.UpdateCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.UpdateCustomer(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.updatecustomer(v=AX.60)
ms:contentKeyID: 62205453
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method

Updates the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function UpdateCustomer ( _
    customer As Customer _
) As NullResponse
'Usage
Dim instance As CustomerService
Dim customer As Customer
Dim returnValue As NullResponse

returnValue = instance.UpdateCustomer(customer)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public NullResponse UpdateCustomer(
    Customer customer
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual NullResponse^ UpdateCustomer(
    Customer^ customer
) sealed
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Call success/failure response.  

#### Implements

[ICustomerService.UpdateCustomer(Customer)](icustomerservice-updatecustomer-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

