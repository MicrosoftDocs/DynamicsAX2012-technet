---
title: OrderService.GetSalesOrdersByCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetSalesOrdersByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetSalesOrdersByCustomer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.orderservice.getsalesordersbycustomer(v=AX.60)
ms:contentKeyID: 62204875
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetSalesOrdersByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrdersByCustomer Method

Get sales orders for the logged in customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetSalesOrdersByCustomer As SalesOrderCollectionResponse
'Usage
Dim instance As OrderService
Dim returnValue As SalesOrderCollectionResponse

returnValue = instance.GetSalesOrdersByCustomer()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public SalesOrderCollectionResponse GetSalesOrdersByCustomer()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual SalesOrderCollectionResponse^ GetSalesOrdersByCustomer() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderCollectionResponse](salesordercollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Sales orders for the logged in customer.  

#### Implements

[IOrderService.GetSalesOrdersByCustomer()](iorderservice-getsalesordersbycustomer-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[OrderService Class](orderservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

