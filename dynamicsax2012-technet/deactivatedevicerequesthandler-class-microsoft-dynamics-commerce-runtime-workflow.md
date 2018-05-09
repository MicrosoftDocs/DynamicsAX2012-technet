---
title: DeactivateDeviceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: DeactivateDeviceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.DeactivateDeviceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.deactivatedevicerequesthandler(v=AX.60)
ms:contentKeyID: 62215191
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DeactivateDeviceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateDeviceRequestHandler Class

Encapsulates the workflow required to deactivate the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DeactivateDeviceRequestHandler _
    Inherits WorkflowRequestHandler(Of DeactivateDeviceRequest, NullResponse)
'Usage
Dim instance As DeactivateDeviceRequestHandler
```

``` csharp
public sealed class DeactivateDeviceRequestHandler : WorkflowRequestHandler<DeactivateDeviceRequest, NullResponse>
```

``` c++
public ref class DeactivateDeviceRequestHandler sealed : public WorkflowRequestHandler<DeactivateDeviceRequest^, NullResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[DeactivateDeviceRequest](deactivatedevicerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [NullResponse](nullresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.DeactivateDeviceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

