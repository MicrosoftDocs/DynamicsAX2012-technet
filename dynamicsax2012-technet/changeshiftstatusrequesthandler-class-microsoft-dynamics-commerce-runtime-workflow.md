---
title: ChangeShiftStatusRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ChangeShiftStatusRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.changeshiftstatusrequesthandler(v=AX.60)
ms:contentKeyID: 62213290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# ChangeShiftStatusRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to update the status of a shift record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ChangeShiftStatusRequestHandler _
    Inherits WorkflowRequestHandler(Of ChangeShiftStatusRequest, ChangeShiftStatusResponse)
'Usage
Dim instance As ChangeShiftStatusRequestHandler
```

``` csharp
public sealed class ChangeShiftStatusRequestHandler : WorkflowRequestHandler<ChangeShiftStatusRequest, ChangeShiftStatusResponse>
```

``` c++
public ref class ChangeShiftStatusRequestHandler sealed : public WorkflowRequestHandler<ChangeShiftStatusRequest^, ChangeShiftStatusResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ChangeShiftStatusRequest](changeshiftstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ChangeShiftStatusResponse](changeshiftstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

