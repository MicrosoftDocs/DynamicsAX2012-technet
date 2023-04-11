---
title: EmployeeTimeRegistrationWorkflowHelper.ValidateTimeRegistrationFunctionalityProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateTimeRegistrationFunctionalityProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.ValidateTimeRegistrationFunctionalityProfile(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.validatetimeregistrationfunctionalityprofile(v=AX.60)
ms:contentKeyID: 62208651
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.ValidateTimeRegistrationFunctionalityProfile
dev_langs:
- CSharp
- C++
- VB
---

# ValidateTimeRegistrationFunctionalityProfile Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee registered stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ValidateTimeRegistrationFunctionalityProfile ( _
    context As RequestContext _
) As Boolean
'Usage
Dim context As RequestContext
Dim returnValue As Boolean

returnValue = EmployeeTimeRegistrationWorkflowHelper.ValidateTimeRegistrationFunctionalityProfile(context)
```

``` csharp
public static bool ValidateTimeRegistrationFunctionalityProfile(
    RequestContext context
)
```

``` c++
public:
static bool ValidateTimeRegistrationFunctionalityProfile(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns bool value of time clock enabled.  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

