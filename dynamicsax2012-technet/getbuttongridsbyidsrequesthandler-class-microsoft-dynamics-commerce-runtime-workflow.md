---
title: GetButtonGridsByIdsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetButtonGridsByIdsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsByIdsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getbuttongridsbyidsrequesthandler(v=AX.60)
ms:contentKeyID: 62213372
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsByIdsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridsByIdsRequestHandler Class

Encapsulates the workflow required to fetch buttongrids by identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetButtonGridsByIdsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetButtonGridsByIdsRequest, GetButtonGridsByIdsResponse)
'Usage
Dim instance As GetButtonGridsByIdsRequestHandler
```

``` csharp
public sealed class GetButtonGridsByIdsRequestHandler : WorkflowRequestHandler<GetButtonGridsByIdsRequest, GetButtonGridsByIdsResponse>
```

``` c++
public ref class GetButtonGridsByIdsRequestHandler sealed : public WorkflowRequestHandler<GetButtonGridsByIdsRequest^, GetButtonGridsByIdsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetButtonGridsByIdsRequest](getbuttongridsbyidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetButtonGridsByIdsResponse](getbuttongridsbyidsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetButtonGridsByIdsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

