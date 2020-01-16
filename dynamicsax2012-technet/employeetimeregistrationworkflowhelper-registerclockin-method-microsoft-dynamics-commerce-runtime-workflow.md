---
title: EmployeeTimeRegistrationWorkflowHelper.RegisterClockIn Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: RegisterClockIn Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterClockIn(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.registerclockin(v=AX.60)
ms:contentKeyID: 65319021
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterClockIn
dev_langs:
- CSharp
- C++
- VB
---

# RegisterClockIn Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function RegisterClockIn ( _
    context As RequestContext _
) As DateTimeOffset
'Usage
Dim context As RequestContext
Dim returnValue As DateTimeOffset

returnValue = EmployeeTimeRegistrationWorkflowHelper.RegisterClockIn(context)
```

``` csharp
public static DateTimeOffset RegisterClockIn(
    RequestContext context
)
```

``` c++
public:
static DateTimeOffset RegisterClockIn(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

