---
title: GetOnlineChannelRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetOnlineChannelRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOnlineChannelRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getonlinechannelrequesthandler(v=AX.60)
ms:contentKeyID: 49832746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOnlineChannelRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetOnlineChannelRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to retrieve the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetOnlineChannelRequestHandler _
    Inherits WorkflowRequestHandler(Of GetOnlineChannelRequest, GetOnlineChannelResponse)
'Usage
Dim instance As GetOnlineChannelRequestHandler
```

``` csharp
public sealed class GetOnlineChannelRequestHandler : WorkflowRequestHandler<GetOnlineChannelRequest, GetOnlineChannelResponse>
```

``` c++
public ref class GetOnlineChannelRequestHandler sealed : public WorkflowRequestHandler<GetOnlineChannelRequest^, GetOnlineChannelResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetOnlineChannelRequest](getonlinechannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetOnlineChannelResponse](getonlinechannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOnlineChannelRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

