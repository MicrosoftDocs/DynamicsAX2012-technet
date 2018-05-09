---
title: EmployeeTimeRegistrationWorkflowHelper.RegisterClockOut Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: RegisterClockOut Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterClockOut(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.registerclockout(v=AX.60)
ms:contentKeyID: 65321026
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.RegisterClockOut
dev_langs:
- CSharp
- C++
- VB
---

# RegisterClockOut Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function RegisterClockOut ( _
    context As RequestContext _
) As DateTimeOffset
'Usage
Dim context As RequestContext
Dim returnValue As DateTimeOffset

returnValue = EmployeeTimeRegistrationWorkflowHelper.RegisterClockOut(context)
```

``` csharp
public static DateTimeOffset RegisterClockOut(
    RequestContext context
)
```

``` c++
public:
static DateTimeOffset RegisterClockOut(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

