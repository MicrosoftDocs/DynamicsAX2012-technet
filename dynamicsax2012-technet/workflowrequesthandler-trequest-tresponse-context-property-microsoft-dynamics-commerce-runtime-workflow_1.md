---
title: WorkflowRequestHandler(TRequest, TResponse).Context Property  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler`2.Context
ms:mtpsurl: https://technet.microsoft.com/library/JJ806282(v=AX.60)
ms:contentKeyID: 49853731
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Context Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the context associated with the current request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Protected Property Context As RequestContext
    Get
    Private Set
'Usage
Dim value As RequestContext

value = Me.Context
```

``` csharp
protected RequestContext Context { get; private set; }
```

``` c++
protected:
property RequestContext^ Context {
    RequestContext^ get ();
    private: void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
Returns [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[WorkflowRequestHandler\<TRequest, TResponse\> Class](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Context Overload](workflowrequesthandler-trequest-tresponse-context-property-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

