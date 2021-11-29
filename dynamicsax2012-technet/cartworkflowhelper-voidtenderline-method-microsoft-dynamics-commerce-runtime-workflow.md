---
title: CartWorkflowHelper.VoidTenderLine Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: VoidTenderLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.VoidTenderLine(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.voidtenderline(v=AX.60)
ms:contentKeyID: 65316181
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.VoidTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# VoidTenderLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub VoidTenderLine ( _
    context As RequestContext, _
    tenderLineBase As TenderLineBase _
)
'Usage
Dim context As RequestContext
Dim tenderLineBase As TenderLineBase

CartWorkflowHelper.VoidTenderLine(context, tenderLineBase)
```

``` csharp
public static void VoidTenderLine(
    RequestContext context,
    TenderLineBase tenderLineBase
)
```

``` c++
public:
static void VoidTenderLine(
    RequestContext^ context, 
    TenderLineBase^ tenderLineBase
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - tenderLineBase  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

