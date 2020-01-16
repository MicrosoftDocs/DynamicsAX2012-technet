---
title: DownloadDataSetRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: DownloadDataSetRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.DownloadDataSetRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.downloaddatasetrequesthandler(v=AX.60)
ms:contentKeyID: 62204958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DownloadDataSetRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# DownloadDataSetRequestHandler Class

Encapsulates the workflow required to download dataset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DownloadDataSetRequestHandler _
    Inherits WorkflowRequestHandler(Of DownloadDataSetRequest, DownloadDataSetResponse)
'Usage
Dim instance As DownloadDataSetRequestHandler
```

``` csharp
public sealed class DownloadDataSetRequestHandler : WorkflowRequestHandler<DownloadDataSetRequest, DownloadDataSetResponse>
```

``` c++
public ref class DownloadDataSetRequestHandler sealed : public WorkflowRequestHandler<DownloadDataSetRequest^, DownloadDataSetResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[DownloadDataSetRequest](downloaddatasetrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [DownloadDataSetResponse](downloaddatasetresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.DownloadDataSetRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

