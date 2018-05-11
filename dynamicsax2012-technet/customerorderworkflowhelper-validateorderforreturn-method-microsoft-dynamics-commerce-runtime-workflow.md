﻿---
title: CustomerOrderWorkflowHelper.ValidateOrderForReturn Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateOrderForReturn Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateOrderForReturn(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.validateorderforreturn(v=AX.60)
ms:contentKeyID: 62212211
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateOrderForReturn
dev_langs:
- CSharp
- C++
- VB
---

# ValidateOrderForReturn Method

Validates the order for return.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateOrderForReturn ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction _
)
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction

CustomerOrderWorkflowHelper.ValidateOrderForReturn(context, _
    salesTransaction)
```

``` csharp
public static void ValidateOrderForReturn(
    RequestContext context,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static void ValidateOrderForReturn(
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

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)
