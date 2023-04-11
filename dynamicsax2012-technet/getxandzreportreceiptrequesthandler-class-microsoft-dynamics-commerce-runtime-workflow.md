---
title: GetXAndZReportReceiptRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetXAndZReportReceiptRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getxandzreportreceiptrequesthandler(v=AX.60)
ms:contentKeyID: 62209809
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetXAndZReportReceiptRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The request handler for GetXAndZReportReceiptRequest class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetXAndZReportReceiptRequestHandler _
    Inherits WorkflowRequestHandler(Of GetXAndZReportReceiptRequest, GetReceiptResponse)
'Usage
Dim instance As GetXAndZReportReceiptRequestHandler
```

``` csharp
public sealed class GetXAndZReportReceiptRequestHandler : WorkflowRequestHandler<GetXAndZReportReceiptRequest, GetReceiptResponse>
```

``` c++
public ref class GetXAndZReportReceiptRequestHandler sealed : public WorkflowRequestHandler<GetXAndZReportReceiptRequest^, GetReceiptResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetXAndZReportReceiptRequest](getxandzreportreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetReceiptResponse](getreceiptresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

