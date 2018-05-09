---
title: GetDeviceConfigurationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetDeviceConfigurationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeviceConfigurationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getdeviceconfigurationrequesthandler(v=AX.60)
ms:contentKeyID: 62208276
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeviceConfigurationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetDeviceConfigurationRequestHandler Class

Request handler to get the device configurations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetDeviceConfigurationRequestHandler _
    Inherits WorkflowRequestHandler(Of GetDeviceConfigurationRequest, GetDeviceConfigurationResponse)
'Usage
Dim instance As GetDeviceConfigurationRequestHandler
```

``` csharp
public sealed class GetDeviceConfigurationRequestHandler : WorkflowRequestHandler<GetDeviceConfigurationRequest, GetDeviceConfigurationResponse>
```

``` c++
public ref class GetDeviceConfigurationRequestHandler sealed : public WorkflowRequestHandler<GetDeviceConfigurationRequest^, GetDeviceConfigurationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetDeviceConfigurationRequest](getdeviceconfigurationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetDeviceConfigurationResponse](getdeviceconfigurationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeviceConfigurationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

