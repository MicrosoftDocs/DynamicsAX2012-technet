---
title: GetCurrentChannelRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCurrentChannelRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrentChannelRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getcurrentchannelrequesthandler(v=AX.60)
ms:contentKeyID: 49830755
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrentChannelRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve the current channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetCurrentChannelRequestHandler _
    Inherits WorkflowRequestHandler(Of GetCurrentChannelRequest, GetCurrentChannelResponse)
'Usage
Dim instance As GetCurrentChannelRequestHandler
```

``` csharp
public sealed class GetCurrentChannelRequestHandler : WorkflowRequestHandler<GetCurrentChannelRequest, GetCurrentChannelResponse>
```

``` c++
public ref class GetCurrentChannelRequestHandler sealed : public WorkflowRequestHandler<GetCurrentChannelRequest^, GetCurrentChannelResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetCurrentChannelRequest](getcurrentchannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetCurrentChannelResponse](getcurrentchannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrentChannelRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

