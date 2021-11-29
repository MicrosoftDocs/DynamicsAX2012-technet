---
title: GetDefaultChannelRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetDefaultChannelRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDefaultChannelRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getdefaultchannelrequesthandler(v=AX.60)
ms:contentKeyID: 62208669
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDefaultChannelRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetDefaultChannelRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve the default channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetDefaultChannelRequestHandler _
    Inherits WorkflowRequestHandler(Of GetDefaultChannelRequest, GetDefaultChannelResponse)
'Usage
Dim instance As GetDefaultChannelRequestHandler
```

``` csharp
public sealed class GetDefaultChannelRequestHandler : WorkflowRequestHandler<GetDefaultChannelRequest, GetDefaultChannelResponse>
```

``` c++
public ref class GetDefaultChannelRequestHandler sealed : public WorkflowRequestHandler<GetDefaultChannelRequest^, GetDefaultChannelResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetDefaultChannelRequest](getdefaultchannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetDefaultChannelResponse](getdefaultchannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDefaultChannelRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

