---
title: CartWorkflowHelper.ValidateSaveCartLinesRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateSaveCartLinesRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateSaveCartLinesRequest(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartLinesRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.validatesavecartlinesrequest(v=AX.60)
ms:contentKeyID: 62214276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ValidateSaveCartLinesRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateSaveCartLinesRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validates the save cart lines request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ValidateSaveCartLinesRequest ( _
    context As RequestContext, _
    request As SaveCartLinesRequest _
)
'Usage
Dim context As RequestContext
Dim request As SaveCartLinesRequest

CartWorkflowHelper.ValidateSaveCartLinesRequest(context, _
    request)
```

``` csharp
public static void ValidateSaveCartLinesRequest(
    RequestContext context,
    SaveCartLinesRequest request
)
```

``` c++
public:
static void ValidateSaveCartLinesRequest(
    RequestContext^ context, 
    SaveCartLinesRequest^ request
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartLinesRequest](savecartlinesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

