---
title: GetListingPublishStatusesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetListingPublishStatusesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingPublishStatusesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getlistingpublishstatusesrequesthandler(v=AX.60)
ms:contentKeyID: 62208099
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingPublishStatusesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetListingPublishStatusesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves all listing publish statuses matching the specified listing identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetListingPublishStatusesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetListingPublishStatusesRequest, GetListingPublishStatusesResponse)
'Usage
Dim instance As GetListingPublishStatusesRequestHandler
```

``` csharp
public sealed class GetListingPublishStatusesRequestHandler : WorkflowRequestHandler<GetListingPublishStatusesRequest, GetListingPublishStatusesResponse>
```

``` c++
public ref class GetListingPublishStatusesRequestHandler sealed : public WorkflowRequestHandler<GetListingPublishStatusesRequest^, GetListingPublishStatusesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetListingPublishStatusesRequest](getlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetListingPublishStatusesResponse](getlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetListingPublishStatusesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

