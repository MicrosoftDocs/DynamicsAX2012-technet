---
title: EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdsByActivities Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetBreakCategoryJobIdsByActivities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdsByActivities(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getbreakcategoryjobidsbyactivities(v=AX.60)
ms:contentKeyID: 62208920
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdsByActivities
dev_langs:
- CSharp
- C++
- VB
---

# GetBreakCategoryJobIdsByActivities Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the break category job identifiers for the given activities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetBreakCategoryJobIdsByActivities ( _
    context As RequestContext, _
    activities As IEnumerable(Of String) _
) As String()
'Usage
Dim context As RequestContext
Dim activities As IEnumerable(Of String)
Dim returnValue As String()

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetBreakCategoryJobIdsByActivities(context, _
    activities)
```

``` csharp
public static string[] GetBreakCategoryJobIdsByActivities(
    RequestContext context,
    IEnumerable<string> activities
)
```

``` c++
public:
static array<String^>^ GetBreakCategoryJobIdsByActivities(
    RequestContext^ context, 
    IEnumerable<String^>^ activities
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - activities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
Returns the activity job identifiers list.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

