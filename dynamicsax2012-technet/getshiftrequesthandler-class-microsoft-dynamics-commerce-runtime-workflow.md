---
title: GetShiftRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetShiftRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShiftRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getshiftrequesthandler(v=AX.60)
ms:contentKeyID: 62202566
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShiftRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftRequestHandler Class

Encapsulates the workflow required to get a single Shift object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetShiftRequestHandler _
    Inherits WorkflowRequestHandler(Of GetShiftRequest, GetShiftResponse)
'Usage
Dim instance As GetShiftRequestHandler
```

``` csharp
public sealed class GetShiftRequestHandler : WorkflowRequestHandler<GetShiftRequest, GetShiftResponse>
```

``` c++
public ref class GetShiftRequestHandler sealed : public WorkflowRequestHandler<GetShiftRequest^, GetShiftResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetShiftRequest](getshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetShiftResponse](getshiftresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetShiftRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

