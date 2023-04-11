---
title: CartWorkflowHelper.TransferSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: TransferSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.TransferSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.transfersalestransaction(v=AX.60)
ms:contentKeyID: 65317762
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.TransferSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# TransferSalesTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub TransferSalesTransaction ( _
    context As RequestContext, _
    transaction As SalesTransaction _
)
'Usage
Dim context As RequestContext
Dim transaction As SalesTransaction

CartWorkflowHelper.TransferSalesTransaction(context, _
    transaction)
```

``` csharp
public static void TransferSalesTransaction(
    RequestContext context,
    SalesTransaction transaction
)
```

``` c++
public:
static void TransferSalesTransaction(
    RequestContext^ context, 
    SalesTransaction^ transaction
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

