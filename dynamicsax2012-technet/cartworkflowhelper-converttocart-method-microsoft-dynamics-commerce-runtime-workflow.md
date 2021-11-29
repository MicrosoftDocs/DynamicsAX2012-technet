---
title: CartWorkflowHelper.ConvertToCart Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ConvertToCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToCart(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.converttocart(v=AX.60)
ms:contentKeyID: 65319999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToCart
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToCart ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction _
) As Cart
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim returnValue As Cart

returnValue = CartWorkflowHelper.ConvertToCart(context, _
    salesTransaction)
```

``` csharp
public static Cart ConvertToCart(
    RequestContext context,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static Cart^ ConvertToCart(
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

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

