---
title: CustomerOrderWorkflowHelper.ValidateCartLineForUpdate Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateCartLineForUpdate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateCartLineForUpdate(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Collections.Generic.Dictionary{System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine,System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.validatecartlineforupdate(v=AX.60)
ms:contentKeyID: 62212534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateCartLineForUpdate
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCartLineForUpdate Method

Validates whether a line can be updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateCartLineForUpdate ( _
    context As RequestContext, _
    newCart As Cart, _
    existingTransaction As SalesTransaction, _
    salesLineByLineId As Dictionary(Of String, SalesLine), _
    cartLine As CartLine, _
    validationFailures As Collection(Of DataValidationFailure) _
)
'Usage
Dim context As RequestContext
Dim newCart As Cart
Dim existingTransaction As SalesTransaction
Dim salesLineByLineId As Dictionary(Of String, SalesLine)
Dim cartLine As CartLine
Dim validationFailures As Collection(Of DataValidationFailure)

CustomerOrderWorkflowHelper.ValidateCartLineForUpdate(context, _
    newCart, existingTransaction, salesLineByLineId, _
    cartLine, validationFailures)
```

``` csharp
public static void ValidateCartLineForUpdate(
    RequestContext context,
    Cart newCart,
    SalesTransaction existingTransaction,
    Dictionary<string, SalesLine> salesLineByLineId,
    CartLine cartLine,
    Collection<DataValidationFailure> validationFailures
)
```

``` c++
public:
static void ValidateCartLineForUpdate(
    RequestContext^ context, 
    Cart^ newCart, 
    SalesTransaction^ existingTransaction, 
    Dictionary<String^, SalesLine^>^ salesLineByLineId, 
    CartLine^ cartLine, 
    Collection<DataValidationFailure^>^ validationFailures
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - newCart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - existingTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesLineByLineId  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - cartLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - validationFailures  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

