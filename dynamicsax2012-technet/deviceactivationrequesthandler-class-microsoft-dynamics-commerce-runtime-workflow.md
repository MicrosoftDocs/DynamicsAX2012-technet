---
title: DeviceActivationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: DeviceActivationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.DeviceActivationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.deviceactivationrequesthandler(v=AX.60)
ms:contentKeyID: 62205168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DeviceActivationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# DeviceActivationRequestHandler Class

Encapsulates the workflow required to activate the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DeviceActivationRequestHandler _
    Inherits WorkflowRequestHandler(Of DeviceActivationRequest, DeviceActivationResponse)
'Usage
Dim instance As DeviceActivationRequestHandler
```

``` csharp
public sealed class DeviceActivationRequestHandler : WorkflowRequestHandler<DeviceActivationRequest, DeviceActivationResponse>
```

``` c++
public ref class DeviceActivationRequestHandler sealed : public WorkflowRequestHandler<DeviceActivationRequest^, DeviceActivationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[DeviceActivationRequest](deviceactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [DeviceActivationResponse](deviceactivationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.DeviceActivationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

