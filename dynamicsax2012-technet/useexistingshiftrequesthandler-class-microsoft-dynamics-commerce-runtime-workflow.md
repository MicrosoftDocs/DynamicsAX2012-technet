---
title: UseExistingShiftRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UseExistingShiftRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UseExistingShiftRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.useexistingshiftrequesthandler(v=AX.60)
ms:contentKeyID: 62212667
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UseExistingShiftRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UseExistingShiftRequestHandler Class

Encapsulates the workflow required to create a shift record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UseExistingShiftRequestHandler _
    Inherits WorkflowRequestHandler(Of UseShiftRequest, UseShiftResponse)
'Usage
Dim instance As UseExistingShiftRequestHandler
```

``` csharp
public sealed class UseExistingShiftRequestHandler : WorkflowRequestHandler<UseShiftRequest, UseShiftResponse>
```

``` c++
public ref class UseExistingShiftRequestHandler sealed : public WorkflowRequestHandler<UseShiftRequest^, UseShiftResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UseShiftRequest](useshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [UseShiftResponse](useshiftresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UseExistingShiftRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

