---
title: CreateShiftRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateShiftRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.createshiftrequesthandler(v=AX.60)
ms:contentKeyID: 62213802
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CreateShiftRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to create a shift record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateShiftRequestHandler _
    Inherits WorkflowRequestHandler(Of CreateShiftRequest, CreateShiftResponse)
'Usage
Dim instance As CreateShiftRequestHandler
```

``` csharp
public sealed class CreateShiftRequestHandler : WorkflowRequestHandler<CreateShiftRequest, CreateShiftResponse>
```

``` c++
public ref class CreateShiftRequestHandler sealed : public WorkflowRequestHandler<CreateShiftRequest^, CreateShiftResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CreateShiftRequest](createshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CreateShiftResponse](createshiftresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

