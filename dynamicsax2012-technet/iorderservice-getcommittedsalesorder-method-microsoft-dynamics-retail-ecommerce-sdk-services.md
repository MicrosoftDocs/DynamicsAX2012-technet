---
title: IOrderService.GetCommittedSalesOrder Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetCommittedSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IOrderService.GetCommittedSalesOrder(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iorderservice.getcommittedsalesorder(v=AX.60)
ms:contentKeyID: 65318462
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IOrderService.GetCommittedSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetCommittedSalesOrder ( _
    salesId As String, _
    includeSalesLines As Boolean _
) As SalesOrderResponse
'Usage
Dim instance As IOrderService
Dim salesId As String
Dim includeSalesLines As Boolean
Dim returnValue As SalesOrderResponse

returnValue = instance.GetCommittedSalesOrder(salesId, _
    includeSalesLines)
```

``` csharp
[OperationContractAttribute]
SalesOrderResponse GetCommittedSalesOrder(
    string salesId,
    bool includeSalesLines
)
```

``` c++
[OperationContractAttribute]
SalesOrderResponse^ GetCommittedSalesOrder(
    String^ salesId, 
    bool includeSalesLines
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeSalesLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IOrderService Interface](iorderservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

