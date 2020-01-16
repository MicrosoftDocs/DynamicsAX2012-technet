---
title: CustomerOrderWorkflowHelper.SaveCustomerOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.SaveCustomerOrder(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.savecustomerorder(v=AX.60)
ms:contentKeyID: 62206891
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.SaveCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerOrder Method

Saves a customer oder using transaction service.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SaveCustomerOrder ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction _
) As SalesOrder
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim returnValue As SalesOrder

returnValue = CustomerOrderWorkflowHelper.SaveCustomerOrder(context, _
    salesTransaction)
```

``` csharp
public static SalesOrder SaveCustomerOrder(
    RequestContext context,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static SalesOrder^ SaveCustomerOrder(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales order representing the saved customer order.  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

