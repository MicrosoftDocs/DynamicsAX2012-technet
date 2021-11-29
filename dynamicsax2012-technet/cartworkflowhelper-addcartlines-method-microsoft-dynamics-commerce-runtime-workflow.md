---
title: CartWorkflowHelper.AddCartLines Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: AddCartLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.AddCartLines(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.addcartlines(v=AX.60)
ms:contentKeyID: 62211014
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.AddCartLines
dev_langs:
- CSharp
- C++
- VB
---

# AddCartLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add cart lines to the given cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AddCartLines ( _
    cart As Cart, _
    cartLines As IEnumerable(Of CartLine) _
)
'Usage
Dim cart As Cart
Dim cartLines As IEnumerable(Of CartLine)

CartWorkflowHelper.AddCartLines(cart, cartLines)
```

``` csharp
public static void AddCartLines(
    Cart cart,
    IEnumerable<CartLine> cartLines
)
```

``` c++
public:
static void AddCartLines(
    Cart^ cart, 
    IEnumerable<CartLine^>^ cartLines
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cartLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

