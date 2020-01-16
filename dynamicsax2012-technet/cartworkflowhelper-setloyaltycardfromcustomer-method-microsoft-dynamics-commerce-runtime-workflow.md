---
title: CartWorkflowHelper.SetLoyaltyCardFromCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SetLoyaltyCardFromCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetLoyaltyCardFromCustomer(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.setloyaltycardfromcustomer(v=AX.60)
ms:contentKeyID: 62213556
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetLoyaltyCardFromCustomer
dev_langs:
- CSharp
- C++
- VB
---

# SetLoyaltyCardFromCustomer Method

Sets the loyalty card in the cart from the customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetLoyaltyCardFromCustomer ( _
    context As RequestContext, _
    cart As Cart _
)
'Usage
Dim context As RequestContext
Dim cart As Cart

CartWorkflowHelper.SetLoyaltyCardFromCustomer(context, _
    cart)
```

``` csharp
public static void SetLoyaltyCardFromCustomer(
    RequestContext context,
    Cart cart
)
```

``` c++
public:
static void SetLoyaltyCardFromCustomer(
    RequestContext^ context, 
    Cart^ cart
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

