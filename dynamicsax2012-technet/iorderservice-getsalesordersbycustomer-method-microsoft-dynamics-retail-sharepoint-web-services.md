---
title: IOrderService.GetSalesOrdersByCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetSalesOrdersByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetSalesOrdersByCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iorderservice.getsalesordersbycustomer(v=AX.60)
ms:contentKeyID: 62206309
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IOrderService.GetSalesOrdersByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrdersByCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get sales orders for the logged in customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetSalesOrdersByCustomer As SalesOrderCollectionResponse
'Usage
Dim instance As IOrderService
Dim returnValue As SalesOrderCollectionResponse

returnValue = instance.GetSalesOrdersByCustomer()
```

``` csharp
[OperationContractAttribute]
SalesOrderCollectionResponse GetSalesOrdersByCustomer()
```

``` c++
[OperationContractAttribute]
SalesOrderCollectionResponse^ GetSalesOrdersByCustomer()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderCollectionResponse](salesordercollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Sales orders for the logged in customer.  

## See Also

#### Reference

[IOrderService Interface](iorderservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

