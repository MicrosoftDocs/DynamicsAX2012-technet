---
title: WorkflowRequestHandler(TRequest, TResponse).Process Method (TRequest) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method (TRequest)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler`2.Process(`0)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ801560(v=AX.60)
ms:contentKeyID: 49840708
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Process Method (TRequest)

Execute method to be overridden by each derived class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Function Process ( _
    request As TRequest _
) As TResponse
'Usage
Dim request As TRequest
Dim returnValue As TResponse

returnValue = Me.Process(request)
```

``` csharp
protected abstract TResponse Process(
    TRequest request
)
```

``` c++
protected:
virtual TResponse Process(
    TRequest request
) abstract
```

#### Parameters

  - request  
    Type: [TRequest](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)  

#### Return Value

Type: [TResponse](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)  
The response.  

## See Also

#### Reference

[WorkflowRequestHandler\<TRequest, TResponse\> Class](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Process Overload](workflowrequesthandler-trequest-tresponse-process-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

