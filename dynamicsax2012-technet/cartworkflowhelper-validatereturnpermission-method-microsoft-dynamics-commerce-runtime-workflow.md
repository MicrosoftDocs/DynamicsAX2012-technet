---
title: CartWorkflowHelper.ValidateReturnPermission Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateReturnPermission Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateReturnPermission(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.validatereturnpermission(v=AX.60)
ms:contentKeyID: 65317823
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateReturnPermission
dev_langs:
- CSharp
- C++
- VB
---

# ValidateReturnPermission Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateReturnPermission ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    cartType As CartType _
)
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim cartType As CartType

CartWorkflowHelper.ValidateReturnPermission(context, _
    salesTransaction, cartType)
```

``` csharp
public static void ValidateReturnPermission(
    RequestContext context,
    SalesTransaction salesTransaction,
    CartType cartType
)
```

``` c++
public:
static void ValidateReturnPermission(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    CartType cartType
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cartType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType](carttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

