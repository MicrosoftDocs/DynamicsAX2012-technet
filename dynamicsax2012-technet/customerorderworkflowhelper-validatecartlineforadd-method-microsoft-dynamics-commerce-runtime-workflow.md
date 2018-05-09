---
title: CustomerOrderWorkflowHelper.ValidateCartLineForAdd Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateCartLineForAdd Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateCartLineForAdd(Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.validatecartlineforadd(v=AX.60)
ms:contentKeyID: 62201740
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.ValidateCartLineForAdd
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCartLineForAdd Method

Validates whether a line can be added.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateCartLineForAdd ( _
    cartLine As CartLine, _
    cart As Cart, _
    salesTransaction As SalesTransaction, _
    validationFailures As Collection(Of DataValidationFailure) _
)
'Usage
Dim cartLine As CartLine
Dim cart As Cart
Dim salesTransaction As SalesTransaction
Dim validationFailures As Collection(Of DataValidationFailure)

CustomerOrderWorkflowHelper.ValidateCartLineForAdd(cartLine, _
    cart, salesTransaction, validationFailures)
```

``` csharp
public static void ValidateCartLineForAdd(
    CartLine cartLine,
    Cart cart,
    SalesTransaction salesTransaction,
    Collection<DataValidationFailure> validationFailures
)
```

``` c++
public:
static void ValidateCartLineForAdd(
    CartLine^ cartLine, 
    Cart^ cart, 
    SalesTransaction^ salesTransaction, 
    Collection<DataValidationFailure^>^ validationFailures
)
```

#### Parameters

  - cartLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - validationFailures  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

