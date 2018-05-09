---
title: CustomerService.UpdateAddresses Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.UpdateAddresses(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.customerservice.updateaddresses(v=AX.60)
ms:contentKeyID: 62204407
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CustomerService.UpdateAddresses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAddresses Method

Updates the addresses.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function UpdateAddresses ( _
    addresses As IEnumerable(Of Address) _
) As NullResponse
'Usage
Dim instance As CustomerService
Dim addresses As IEnumerable(Of Address)
Dim returnValue As NullResponse

returnValue = instance.UpdateAddresses(addresses)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public NullResponse UpdateAddresses(
    IEnumerable<Address> addresses
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual NullResponse^ UpdateAddresses(
    IEnumerable<Address^>^ addresses
) sealed
```

#### Parameters

  - addresses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Call success/failure response.  

#### Implements

[ICustomerService.UpdateAddresses(IEnumerable\<Address\>)](icustomerservice-updateaddresses-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CustomerService Class](customerservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

