---
title: OrderService.GetCommittedSalesOrderByConfirmationId Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetCommittedSalesOrderByConfirmationId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetCommittedSalesOrderByConfirmationId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.orderservice.getcommittedsalesorderbyconfirmationid(v=AX.60)
ms:contentKeyID: 62202971
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.OrderService.GetCommittedSalesOrderByConfirmationId
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrderByConfirmationId Method

Gets the committed Sales order matching the confirmationId.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetCommittedSalesOrderByConfirmationId ( _
    confirmationId As String _
) As SalesOrderResponse
'Usage
Dim instance As OrderService
Dim confirmationId As String
Dim returnValue As SalesOrderResponse

returnValue = instance.GetCommittedSalesOrderByConfirmationId(confirmationId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public SalesOrderResponse GetCommittedSalesOrderByConfirmationId(
    string confirmationId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual SalesOrderResponse^ GetCommittedSalesOrderByConfirmationId(
    String^ confirmationId
) sealed
```

#### Parameters

  - confirmationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Sales Order response containing the matching sales order.  

#### Implements

[IOrderService.GetCommittedSalesOrderByConfirmationId(String)](iorderservice-getcommittedsalesorderbyconfirmationid-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[OrderService Class](orderservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

