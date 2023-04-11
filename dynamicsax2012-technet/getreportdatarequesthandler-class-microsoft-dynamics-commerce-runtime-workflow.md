---
title: GetReportDataRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetReportDataRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReportDataRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getreportdatarequesthandler(v=AX.60)
ms:contentKeyID: 62205391
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReportDataRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetReportDataRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get datatable for reports data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetReportDataRequestHandler _
    Inherits WorkflowRequestHandler(Of GetReportDataRequest, GetReportDataResponse)
'Usage
Dim instance As GetReportDataRequestHandler
```

``` csharp
public sealed class GetReportDataRequestHandler : WorkflowRequestHandler<GetReportDataRequest, GetReportDataResponse>
```

``` c++
public ref class GetReportDataRequestHandler sealed : public WorkflowRequestHandler<GetReportDataRequest^, GetReportDataResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetReportDataRequest](getreportdatarequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetReportDataResponse](getreportdataresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReportDataRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

