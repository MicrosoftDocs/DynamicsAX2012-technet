---
title: EmployeeTimeRegistrationWorkflowHelper.RegisterEmployeeBreak Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: RegisterEmployeeBreak Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterEmployeeBreak(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.registeremployeebreak(v=AX.60)
ms:contentKeyID: 62210658
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterEmployeeBreak
dev_langs:
- CSharp
- C++
- VB
---

# RegisterEmployeeBreak Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Register the time for employee break.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function RegisterEmployeeBreak ( _
    context As RequestContext, _
    jobId As String _
) As DateTimeOffset
'Usage
Dim context As RequestContext
Dim jobId As String
Dim returnValue As DateTimeOffset

returnValue = EmployeeTimeRegistrationWorkflowHelper.RegisterEmployeeBreak(context, _
    jobId)
```

``` csharp
public static DateTimeOffset RegisterEmployeeBreak(
    RequestContext context,
    string jobId
)
```

``` c++
public:
static DateTimeOffset RegisterEmployeeBreak(
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

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns the activity DateTimeOffset in channel local time zone.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

