---
title: CartWorkflowHelper.ConvertToSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ConvertToSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.converttosalestransaction(v=AX.60)
ms:contentKeyID: 65322820
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToSalesTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToSalesTransaction ( _
    cart As Cart _
) As SalesTransaction
'Usage
Dim cart As Cart
Dim returnValue As SalesTransaction

returnValue = CartWorkflowHelper.ConvertToSalesTransaction(cart)
```

``` csharp
public static SalesTransaction ConvertToSalesTransaction(
    Cart cart
)
```

``` c++
public:
static SalesTransaction^ ConvertToSalesTransaction(
    Cart^ cart
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

