﻿---
title: CustomerService.CreateCustomerByEmail Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateCustomerByEmail Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.CreateCustomerByEmail(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.createcustomerbyemail(v=AX.60)
ms:contentKeyID: 62201844
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.CreateCustomerByEmail
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerByEmail Method

Creates the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function CreateCustomerByEmail ( _
    emailAddress As String, _
    activationToken As String _
) As CustomerResponse
'Usage
Dim instance As CustomerService
Dim emailAddress As String
Dim activationToken As String
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomerByEmail(emailAddress, _
    activationToken)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public CustomerResponse CreateCustomerByEmail(
    string emailAddress,
    string activationToken
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual CustomerResponse^ CreateCustomerByEmail(
    String^ emailAddress, 
    String^ activationToken
) sealed
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A customer response.  

#### Implements

[ICustomerService.CreateCustomerByEmail(String, String)](icustomerservice-createcustomerbyemail-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)
