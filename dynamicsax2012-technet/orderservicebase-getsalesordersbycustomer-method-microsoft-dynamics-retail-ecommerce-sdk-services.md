---
title: OrderServiceBase.GetSalesOrdersByCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetSalesOrdersByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase.GetSalesOrdersByCustomer(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.orderservicebase.getsalesordersbycustomer(v=AX.60)
ms:contentKeyID: 65317201
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase.GetSalesOrdersByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrdersByCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetSalesOrdersByCustomer ( _
    includeSalesLines As Boolean _
) As SalesOrderCollectionResponse
'Usage
Dim instance As OrderServiceBase
Dim includeSalesLines As Boolean
Dim returnValue As SalesOrderCollectionResponse

returnValue = instance.GetSalesOrdersByCustomer(includeSalesLines)
```

``` csharp
public virtual SalesOrderCollectionResponse GetSalesOrdersByCustomer(
    bool includeSalesLines
)
```

``` c++
public:
virtual SalesOrderCollectionResponse^ GetSalesOrdersByCustomer(
    bool includeSalesLines
)
```

#### Parameters

  - includeSalesLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderCollectionResponse](salesordercollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IOrderService.GetSalesOrdersByCustomer(Boolean)](iorderservice-getsalesordersbycustomer-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[OrderServiceBase Class](orderservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

