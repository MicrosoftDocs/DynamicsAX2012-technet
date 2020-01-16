---
title: SalesOrderService.GetSalesOrderSummaryFromContainer Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetSalesOrderSummaryFromContainer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService.GetSalesOrderSummaryFromContainer(System.Collections.IList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.salesorderservice.getsalesordersummaryfromcontainer(v=AX.60)
ms:contentKeyID: 49832725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService.GetSalesOrderSummaryFromContainer
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrderSummaryFromContainer Method

Get sales order header information from AXContainer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function GetSalesOrderSummaryFromContainer ( _
    salesRecord As IList _
) As SalesOrder
'Usage
Dim salesRecord As IList
Dim returnValue As SalesOrder

returnValue = SalesOrderService.GetSalesOrderSummaryFromContainer(salesRecord)
```

``` csharp
protected static SalesOrder GetSalesOrderSummaryFromContainer(
    IList salesRecord
)
```

``` c++
protected:
static SalesOrder^ GetSalesOrderSummaryFromContainer(
    IList^ salesRecord
)
```

#### Parameters

  - salesRecord  
    Type: [System.Collections.IList](https://technet.microsoft.com/library/30ft6hw7\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales order.  

## See Also

#### Reference

[SalesOrderService Class](salesorderservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

