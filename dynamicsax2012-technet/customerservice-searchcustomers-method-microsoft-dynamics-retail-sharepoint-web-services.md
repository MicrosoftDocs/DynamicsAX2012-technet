---
title: CustomerService.SearchCustomers Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.SearchCustomers(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.searchcustomers(v=AX.60)
ms:contentKeyID: 62204457
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Search for a customer given the corresponding email address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function SearchCustomers ( _
    emailAddress As String _
) As Boolean
'Usage
Dim instance As CustomerService
Dim emailAddress As String
Dim returnValue As Boolean

returnValue = instance.SearchCustomers(emailAddress)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public bool SearchCustomers(
    string emailAddress
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual bool SearchCustomers(
    String^ emailAddress
) sealed
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the customer exists, false otherwise.  

#### Implements

[ICustomerService.SearchCustomers(String)](icustomerservice-searchcustomers-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

