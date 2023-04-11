---
title: EmployeeTimeRegistrationWorkflowHelper.GetLatestActivity Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetLatestActivity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetLatestActivity(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getlatestactivity(v=AX.60)
ms:contentKeyID: 62210919
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetLatestActivity
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestActivity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the latest activity of the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetLatestActivity ( _
    context As RequestContext _
) As EmployeeActivity
'Usage
Dim context As RequestContext
Dim returnValue As EmployeeActivity

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetLatestActivity(context)
```

``` csharp
public static EmployeeActivity GetLatestActivity(
    RequestContext context
)
```

``` c++
public:
static EmployeeActivity^ GetLatestActivity(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The latest employee activity.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

