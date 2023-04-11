---
title: CustomerOrderWorkflowHelper.CustomerOrderCartValidations Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CustomerOrderCartValidations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.CustomerOrderCartValidations(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.customerordercartvalidations(v=AX.60)
ms:contentKeyID: 62210911
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.CustomerOrderCartValidations
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderCartValidations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validates a customer order cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CustomerOrderCartValidations ( _
    context As RequestContext, _
    cart As Cart, _
    salesTransaction As SalesTransaction, _
    returnedSalesTransaction As SalesTransaction, _
    validationResults As CartLineValidationResults _
)
'Usage
Dim context As RequestContext
Dim cart As Cart
Dim salesTransaction As SalesTransaction
Dim returnedSalesTransaction As SalesTransaction
Dim validationResults As CartLineValidationResults

CustomerOrderWorkflowHelper.CustomerOrderCartValidations(context, _
    cart, salesTransaction, returnedSalesTransaction, _
    validationResults)
```

``` csharp
public static void CustomerOrderCartValidations(
    RequestContext context,
    Cart cart,
    SalesTransaction salesTransaction,
    SalesTransaction returnedSalesTransaction,
    CartLineValidationResults validationResults
)
```

``` c++
public:
static void CustomerOrderCartValidations(
    RequestContext^ context, 
    Cart^ cart, 
    SalesTransaction^ salesTransaction, 
    SalesTransaction^ returnedSalesTransaction, 
    CartLineValidationResults^ validationResults
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - returnedSalesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - validationResults  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

