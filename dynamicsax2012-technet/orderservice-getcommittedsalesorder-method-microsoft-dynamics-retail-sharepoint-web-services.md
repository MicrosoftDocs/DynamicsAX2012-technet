---
title: OrderService.GetCommittedSalesOrder Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetCommittedSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetCommittedSalesOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.orderservice.getcommittedsalesorder(v=AX.60)
ms:contentKeyID: 62203011
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetCommittedSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the committed Sales order matching the salesId.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetCommittedSalesOrder ( _
    salesId As String _
) As SalesOrderResponse
'Usage
Dim instance As OrderService
Dim salesId As String
Dim returnValue As SalesOrderResponse

returnValue = instance.GetCommittedSalesOrder(salesId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public SalesOrderResponse GetCommittedSalesOrder(
    string salesId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual SalesOrderResponse^ GetCommittedSalesOrder(
    String^ salesId
) sealed
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Sales Order response containing the matching sales order.  

#### Implements

[IOrderService.GetCommittedSalesOrder(String)](iorderservice-getcommittedsalesorder-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[OrderService Class](orderservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

