---
title: CustomerOrderWorkflowHelper.SaveTransactionAndConvertToCart Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveTransactionAndConvertToCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.SaveTransactionAndConvertToCart(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.savetransactionandconverttocart(v=AX.60)
ms:contentKeyID: 62211753
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.SaveTransactionAndConvertToCart
dev_langs:
- CSharp
- C++
- VB
---

# SaveTransactionAndConvertToCart Method

Saves the order as a transaction and converts it to a cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SaveTransactionAndConvertToCart ( _
    context As RequestContext, _
    order As SalesOrder _
) As Cart
'Usage
Dim context As RequestContext
Dim order As SalesOrder
Dim returnValue As Cart

returnValue = CustomerOrderWorkflowHelper.SaveTransactionAndConvertToCart(context, _
    order)
```

``` csharp
public static Cart SaveTransactionAndConvertToCart(
    RequestContext context,
    SalesOrder order
)
```

``` c++
public:
static Cart^ SaveTransactionAndConvertToCart(
    RequestContext^ context, 
    SalesOrder^ order
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - order  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The converted cart.  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

