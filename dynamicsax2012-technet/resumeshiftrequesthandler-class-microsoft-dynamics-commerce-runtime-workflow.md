---
title: ResumeShiftRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ResumeShiftRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.resumeshiftrequesthandler(v=AX.60)
ms:contentKeyID: 62206026
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# ResumeShiftRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to create a shift record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ResumeShiftRequestHandler _
    Inherits WorkflowRequestHandler(Of ResumeShiftRequest, ResumeShiftResponse)
'Usage
Dim instance As ResumeShiftRequestHandler
```

``` csharp
public sealed class ResumeShiftRequestHandler : WorkflowRequestHandler<ResumeShiftRequest, ResumeShiftResponse>
```

``` c++
public ref class ResumeShiftRequestHandler sealed : public WorkflowRequestHandler<ResumeShiftRequest^, ResumeShiftResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ResumeShiftRequest](resumeshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ResumeShiftResponse](resumeshiftresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

