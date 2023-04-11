---
title: OrderServiceBase.GetCommittedSalesOrderByConfirmationId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetCommittedSalesOrderByConfirmationId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase.GetCommittedSalesOrderByConfirmationId(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.orderservicebase.getcommittedsalesorderbyconfirmationid(v=AX.60)
ms:contentKeyID: 65317437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase.GetCommittedSalesOrderByConfirmationId
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrderByConfirmationId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetCommittedSalesOrderByConfirmationId ( _
    confirmationId As String, _
    includeSalesLines As Boolean _
) As SalesOrderResponse
'Usage
Dim instance As OrderServiceBase
Dim confirmationId As String
Dim includeSalesLines As Boolean
Dim returnValue As SalesOrderResponse

returnValue = instance.GetCommittedSalesOrderByConfirmationId(confirmationId, _
    includeSalesLines)
```

``` csharp
public virtual SalesOrderResponse GetCommittedSalesOrderByConfirmationId(
    string confirmationId,
    bool includeSalesLines
)
```

``` c++
public:
virtual SalesOrderResponse^ GetCommittedSalesOrderByConfirmationId(
    String^ confirmationId, 
    bool includeSalesLines
)
```

#### Parameters

  - confirmationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeSalesLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderResponse](salesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IOrderService.GetCommittedSalesOrderByConfirmationId(String, Boolean)](iorderservice-getcommittedsalesorderbyconfirmationid-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[OrderServiceBase Class](orderservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

