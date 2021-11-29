---
title: UpdateChannelPropertiesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UpdateChannelPropertiesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateChannelPropertiesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.updatechannelpropertiesrequesthandler(v=AX.60)
ms:contentKeyID: 49826724
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateChannelPropertiesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelPropertiesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to save the channel-specific properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class UpdateChannelPropertiesRequestHandler _
    Inherits WorkflowRequestHandler(Of UpdateChannelPropertiesRequest, UpdateChannelPropertiesResponse)
'Usage
Dim instance As UpdateChannelPropertiesRequestHandler
```

``` csharp
public sealed class UpdateChannelPropertiesRequestHandler : WorkflowRequestHandler<UpdateChannelPropertiesRequest, UpdateChannelPropertiesResponse>
```

``` c++
public ref class UpdateChannelPropertiesRequestHandler sealed : public WorkflowRequestHandler<UpdateChannelPropertiesRequest^, UpdateChannelPropertiesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[UpdateChannelPropertiesRequest](updatechannelpropertiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [UpdateChannelPropertiesResponse](updatechannelpropertiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateChannelPropertiesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

