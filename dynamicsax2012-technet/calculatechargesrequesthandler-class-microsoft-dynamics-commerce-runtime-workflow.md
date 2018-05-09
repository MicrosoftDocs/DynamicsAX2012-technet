---
title: CalculateChargesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CalculateChargesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateChargesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.calculatechargesrequesthandler(v=AX.60)
ms:contentKeyID: 62210238
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateChargesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CalculateChargesRequestHandler Class

Handles workflow for CalculateCharges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CalculateChargesRequestHandler _
    Inherits WorkflowRequestHandler(Of CalculateChargesRequest, CalculateChargesResponse)
'Usage
Dim instance As CalculateChargesRequestHandler
```

``` csharp
public sealed class CalculateChargesRequestHandler : WorkflowRequestHandler<CalculateChargesRequest, CalculateChargesResponse>
```

``` c++
public ref class CalculateChargesRequestHandler sealed : public WorkflowRequestHandler<CalculateChargesRequest^, CalculateChargesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CalculateChargesRequest](calculatechargesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CalculateChargesResponse](calculatechargesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateChargesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

