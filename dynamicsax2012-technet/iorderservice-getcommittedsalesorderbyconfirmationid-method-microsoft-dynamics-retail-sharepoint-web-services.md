---
title: IOrderService.GetCommittedSalesOrderByConfirmationId Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetCommittedSalesOrderByConfirmationId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetCommittedSalesOrderByConfirmationId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iorderservice.getcommittedsalesorderbyconfirmationid(v=AX.60)
ms:contentKeyID: 62207531
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetCommittedSalesOrderByConfirmationId
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrderByConfirmationId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get sales order that is successfully committed to the ERP.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetCommittedSalesOrderByConfirmationId ( _
    confirmationId As String _
) As SalesOrderResponse
'Usage
Dim instance As IOrderService
Dim confirmationId As String
Dim returnValue As SalesOrderResponse

returnValue = instance.GetCommittedSalesOrderByConfirmationId(confirmationId)
```

``` csharp
[OperationContractAttribute]
SalesOrderResponse GetCommittedSalesOrderByConfirmationId(
    string confirmationId
)
```

``` c++
[OperationContractAttribute]
SalesOrderResponse^ GetCommittedSalesOrderByConfirmationId(
    String^ confirmationId
)
```

#### Parameters

  - confirmationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The sales order.  

## See Also

#### Reference

[IOrderService Interface](iorderservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

