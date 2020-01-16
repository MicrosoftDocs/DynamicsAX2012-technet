---
title: EmployeeTimeRegistrationRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationrequesthandler.process(v=AX.60)
ms:contentKeyID: 62202610
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method

Workflow to process employee time clock activities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As EmployeeTimeRegistrationRequest _
) As EmployeeTimeRegistrationResponse
'Usage
Dim request As EmployeeTimeRegistrationRequest
Dim returnValue As EmployeeTimeRegistrationResponse

returnValue = Me.Process(request)
```

``` csharp
protected override EmployeeTimeRegistrationResponse Process(
    EmployeeTimeRegistrationRequest request
)
```

``` c++
protected:
virtual EmployeeTimeRegistrationResponse^ Process(
    EmployeeTimeRegistrationRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[EmployeeTimeRegistrationRequestHandler Class](employeetimeregistrationrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

