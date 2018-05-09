---
title: EmployeeTimeRegistrationRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: EmployeeTimeRegistrationRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationrequesthandler(v=AX.60)
ms:contentKeyID: 62207981
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeTimeRegistrationRequestHandler Class

Encapsulates the workflow to process the employee time clock registration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class EmployeeTimeRegistrationRequestHandler _
    Inherits WorkflowRequestHandler(Of EmployeeTimeRegistrationRequest, EmployeeTimeRegistrationResponse)
'Usage
Dim instance As EmployeeTimeRegistrationRequestHandler
```

``` csharp
public class EmployeeTimeRegistrationRequestHandler : WorkflowRequestHandler<EmployeeTimeRegistrationRequest, EmployeeTimeRegistrationResponse>
```

``` c++
public ref class EmployeeTimeRegistrationRequestHandler : public WorkflowRequestHandler<EmployeeTimeRegistrationRequest^, EmployeeTimeRegistrationResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[EmployeeTimeRegistrationRequest](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [EmployeeTimeRegistrationResponse](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

