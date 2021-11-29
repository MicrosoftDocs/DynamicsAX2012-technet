---
title: GetSupportedReportsRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetSupportedReportsRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedReportsRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getsupportedreportsrequesthandler(v=AX.60)
ms:contentKeyID: 62210027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedReportsRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedReportsRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get reports configured.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetSupportedReportsRequestHandler _
    Inherits WorkflowRequestHandler(Of GetSupportedReportsRequest, GetSupportedReportsResponse)
'Usage
Dim instance As GetSupportedReportsRequestHandler
```

``` csharp
public sealed class GetSupportedReportsRequestHandler : WorkflowRequestHandler<GetSupportedReportsRequest, GetSupportedReportsResponse>
```

``` c++
public ref class GetSupportedReportsRequestHandler sealed : public WorkflowRequestHandler<GetSupportedReportsRequest^, GetSupportedReportsResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetSupportedReportsRequest](getsupportedreportsrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetSupportedReportsResponse](getsupportedreportsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedReportsRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

