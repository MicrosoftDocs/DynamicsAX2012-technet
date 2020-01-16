---
title: CartWorkflowHelper.UpdateAccountDepositTransactionFields Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UpdateAccountDepositTransactionFields Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.UpdateAccountDepositTransactionFields(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.updateaccountdeposittransactionfields(v=AX.60)
ms:contentKeyID: 65320066
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.UpdateAccountDepositTransactionFields
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAccountDepositTransactionFields Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub UpdateAccountDepositTransactionFields ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    cart As Cart _
)
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim cart As Cart

CartWorkflowHelper.UpdateAccountDepositTransactionFields(context, _
    salesTransaction, cart)
```

``` csharp
public static void UpdateAccountDepositTransactionFields(
    RequestContext context,
    SalesTransaction salesTransaction,
    Cart cart
)
```

``` c++
public:
static void UpdateAccountDepositTransactionFields(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    Cart^ cart
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

