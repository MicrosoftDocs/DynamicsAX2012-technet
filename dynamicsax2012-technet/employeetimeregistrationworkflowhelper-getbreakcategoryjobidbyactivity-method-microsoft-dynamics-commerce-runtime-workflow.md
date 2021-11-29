---
title: EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdByActivity Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetBreakCategoryJobIdByActivity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdByActivity(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getbreakcategoryjobidbyactivity(v=AX.60)
ms:contentKeyID: 62214808
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdByActivity
dev_langs:
- CSharp
- C++
- VB
---

# GetBreakCategoryJobIdByActivity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the break category job identifier for the given activity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetBreakCategoryJobIdByActivity ( _
    context As RequestContext, _
    activity As String _
) As String
'Usage
Dim context As RequestContext
Dim activity As String
Dim returnValue As String

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdByActivity(context, _
    activity)
```

``` csharp
public static string GetBreakCategoryJobIdByActivity(
    RequestContext context,
    string activity
)
```

``` c++
public:
static String^ GetBreakCategoryJobIdByActivity(
    RequestContext^ context, 
    String^ activity
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - activity  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns the activity job identifier.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

