---
title: CartWorkflowHelper.ValidateUpdateCartRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateUpdateCartRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateUpdateCartRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.validateupdatecartrequest(v=AX.60)
ms:contentKeyID: 62204788
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateUpdateCartRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateUpdateCartRequest Method

Validates the update cart request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateUpdateCartRequest ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    returnedSalesTransaction As SalesTransaction, _
    newCart As Cart, _
    isGiftCardOperation As Boolean _
)
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim returnedSalesTransaction As SalesTransaction
Dim newCart As Cart
Dim isGiftCardOperation As Boolean

CartWorkflowHelper.ValidateUpdateCartRequest(context, _
    salesTransaction, returnedSalesTransaction, _
    newCart, isGiftCardOperation)
```

``` csharp
public static void ValidateUpdateCartRequest(
    RequestContext context,
    SalesTransaction salesTransaction,
    SalesTransaction returnedSalesTransaction,
    Cart newCart,
    bool isGiftCardOperation
)
```

``` c++
public:
static void ValidateUpdateCartRequest(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    SalesTransaction^ returnedSalesTransaction, 
    Cart^ newCart, 
    bool isGiftCardOperation
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - returnedSalesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - newCart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isGiftCardOperation  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md">CartValidationException</a></td>
<td><p>Invalid cart.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

