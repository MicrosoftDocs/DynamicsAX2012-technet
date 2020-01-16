---
title: WorkflowRequestHandler(TRequest, TResponse) Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: WorkflowRequestHandler(TRequest, TResponse) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler`2
ms:mtpsurl: https://technet.microsoft.com/library/JJ764791(v=AX.60)
ms:contentKeyID: 49848193
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler`2
dev_langs:
- CSharp
- C++
- VB
---

# WorkflowRequestHandler(TRequest, TResponse) Class

Abstract base class for all request handlers for workflow.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class WorkflowRequestHandler(Of TRequest As Request, TResponse As Response) _
    Implements IRequestHandler
'Usage
Dim instance As WorkflowRequestHandler(Of TRequest, TResponse)
```

``` csharp
public abstract class WorkflowRequestHandler<TRequest, TResponse> : IRequestHandler
where TRequest : Request
where TResponse : Response
```

``` c++
generic<typename TRequest, typename TResponse>
where TRequest : Request
where TResponse : Response
public ref class WorkflowRequestHandler abstract : IRequestHandler
```

#### Type Parameters

  - TRequest

<!-- end list -->

  - TResponse

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler\<TRequest, TResponse\>  
    [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequestHandler](makepaymentrequesthandler-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

