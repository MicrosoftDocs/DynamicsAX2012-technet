---
title: CartWorkflowHelper.SaveSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SaveSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.savesalestransaction(v=AX.60)
ms:contentKeyID: 62209160
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SaveSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SaveSalesTransaction Method

Saves the context's sales transaction to the DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SaveSalesTransaction ( _
    context As RequestContext, _
    transaction As SalesTransaction _
)
'Usage
Dim context As RequestContext
Dim transaction As SalesTransaction

CartWorkflowHelper.SaveSalesTransaction(context, _
    transaction)
```

``` csharp
public static void SaveSalesTransaction(
    RequestContext context,
    SalesTransaction transaction
)
```

``` c++
public:
static void SaveSalesTransaction(
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

