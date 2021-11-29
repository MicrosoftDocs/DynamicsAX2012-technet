---
title: EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryByJob Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetBreakCategoryByJob Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryByJob(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getbreakcategorybyjob(v=AX.60)
ms:contentKeyID: 62207904
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryByJob
dev_langs:
- CSharp
- C++
- VB
---

# GetBreakCategoryByJob Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the break category name based on given job identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetBreakCategoryByJob ( _
    context As RequestContext, _
    jobId As String _
) As String
'Usage
Dim context As RequestContext
Dim jobId As String
Dim returnValue As String

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryByJob(context, _
    jobId)
```

``` csharp
public static string GetBreakCategoryByJob(
    RequestContext context,
    string jobId
)
```

``` c++
public:
static String^ GetBreakCategoryByJob(
    RequestContext^ context, 
    String^ jobId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - jobId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns the break category.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

