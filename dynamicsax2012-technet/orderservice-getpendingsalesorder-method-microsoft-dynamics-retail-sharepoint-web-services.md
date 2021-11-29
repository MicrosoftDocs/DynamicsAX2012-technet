---
title: OrderService.GetPendingSalesOrder Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPendingSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetPendingSalesOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.orderservice.getpendingsalesorder(v=AX.60)
ms:contentKeyID: 62205245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetPendingSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetPendingSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the Pending sales order matching the transactionId.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetPendingSalesOrder ( _
    transactionId As String _
) As SalesOrderResponse
'Usage
Dim instance As OrderService
Dim transactionId As String
Dim returnValue As SalesOrderResponse

returnValue = instance.GetPendingSalesOrder(transactionId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public SalesOrderResponse GetPendingSalesOrder(
    string transactionId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual SalesOrderResponse^ GetPendingSalesOrder(
    String^ transactionId
) sealed
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Sales Order response containing the matching sales order.  

#### Implements

[IOrderService.GetPendingSalesOrder(String)](iorderservice-getpendingsalesorder-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[OrderService Class](orderservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

