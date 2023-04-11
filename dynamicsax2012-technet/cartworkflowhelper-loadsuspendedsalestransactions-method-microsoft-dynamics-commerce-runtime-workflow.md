---
title: CartWorkflowHelper.LoadSuspendedSalesTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: LoadSuspendedSalesTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSuspendedSalesTransactions(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.loadsuspendedsalestransactions(v=AX.60)
ms:contentKeyID: 62206432
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSuspendedSalesTransactions
dev_langs:
- CSharp
- C++
- VB
---

# LoadSuspendedSalesTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Load all the suspended transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function LoadSuspendedSalesTransactions ( _
    context As RequestContext _
) As IEnumerable(Of SalesTransaction)
'Usage
Dim context As RequestContext
Dim returnValue As IEnumerable(Of SalesTransaction)

returnValue = CartWorkflowHelper.LoadSuspendedSalesTransactions(context)
```

``` csharp
public static IEnumerable<SalesTransaction> LoadSuspendedSalesTransactions(
    RequestContext context
)
```

``` c++
public:
static IEnumerable<SalesTransaction^>^ LoadSuspendedSalesTransactions(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The loaded sales transaction.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

