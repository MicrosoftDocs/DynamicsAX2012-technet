---
title: GetButtonGridsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetButtonGridsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getbuttongridsrequesthandler(v=AX.60)
ms:contentKeyID: 62213784
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to fetch buttongrids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetButtonGridsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetButtonGridsRequest, GetButtonGridsResponse)
'Usage
Dim instance As GetButtonGridsRequestHandler
```

``` csharp
public sealed class GetButtonGridsRequestHandler : WorkflowRequestHandler<GetButtonGridsRequest, GetButtonGridsResponse>
```

``` c++
public ref class GetButtonGridsRequestHandler sealed : public WorkflowRequestHandler<GetButtonGridsRequest^, GetButtonGridsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetButtonGridsRequest](getbuttongridsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetButtonGridsResponse](getbuttongridsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

