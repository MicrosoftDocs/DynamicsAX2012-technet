---
title: GetChannelConfigurationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetChannelConfigurationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelConfigurationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getchannelconfigurationrequesthandler(v=AX.60)
ms:contentKeyID: 62210197
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelConfigurationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelConfigurationRequestHandler Class

Encapsulates the workflow required to retrieve channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetChannelConfigurationRequestHandler _
    Inherits WorkflowRequestHandler(Of GetChannelConfigurationRequest, GetChannelConfigurationResponse)
'Usage
Dim instance As GetChannelConfigurationRequestHandler
```

``` csharp
public sealed class GetChannelConfigurationRequestHandler : WorkflowRequestHandler<GetChannelConfigurationRequest, GetChannelConfigurationResponse>
```

``` c++
public ref class GetChannelConfigurationRequestHandler sealed : public WorkflowRequestHandler<GetChannelConfigurationRequest^, GetChannelConfigurationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetChannelConfigurationRequest](getchannelconfigurationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetChannelConfigurationResponse](getchannelconfigurationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelConfigurationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

