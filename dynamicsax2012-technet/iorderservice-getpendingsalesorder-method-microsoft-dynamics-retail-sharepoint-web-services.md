---
title: IOrderService.GetPendingSalesOrder Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPendingSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetPendingSalesOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iorderservice.getpendingsalesorder(v=AX.60)
ms:contentKeyID: 62207498
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetPendingSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetPendingSalesOrder Method

Get sales order that is pending commitment to the ERP.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetPendingSalesOrder ( _
    transactionId As String _
) As SalesOrderResponse
'Usage
Dim instance As IOrderService
Dim transactionId As String
Dim returnValue As SalesOrderResponse

returnValue = instance.GetPendingSalesOrder(transactionId)
```

``` csharp
[OperationContractAttribute]
SalesOrderResponse GetPendingSalesOrder(
    string transactionId
)
```

``` c++
[OperationContractAttribute]
SalesOrderResponse^ GetPendingSalesOrder(
    String^ transactionId
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The sales order.  

## See Also

#### Reference

[IOrderService Interface](iorderservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

