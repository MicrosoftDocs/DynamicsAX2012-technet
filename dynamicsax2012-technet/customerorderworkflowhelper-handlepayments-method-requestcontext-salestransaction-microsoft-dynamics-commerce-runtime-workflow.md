---
title: CustomerOrderWorkflowHelper.HandlePayments Method (RequestContext, SalesTransaction) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: HandlePayments Method (RequestContext, SalesTransaction)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.HandlePayments(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.handlepayments(v=AX.60)
ms:contentKeyID: 62210101
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# HandlePayments Method (RequestContext, SalesTransaction)

Handles payments for customer orders, it includes: \* Capturing deposit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function HandlePayments ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim returnValue As SalesTransaction

returnValue = CustomerOrderWorkflowHelper.HandlePayments(context, _
    salesTransaction)
```

``` csharp
public static SalesTransaction HandlePayments(
    RequestContext context,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static SalesTransaction^ HandlePayments(
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

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Updated sales transaction.  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[HandlePayments Overload](customerorderworkflowhelper-handlepayments-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

