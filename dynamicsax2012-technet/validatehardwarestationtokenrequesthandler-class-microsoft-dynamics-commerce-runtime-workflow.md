---
title: ValidateHardwareStationTokenRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ValidateHardwareStationTokenRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateHardwareStationTokenRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.validatehardwarestationtokenrequesthandler(v=AX.60)
ms:contentKeyID: 62213355
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateHardwareStationTokenRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# ValidateHardwareStationTokenRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow for validating a hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ValidateHardwareStationTokenRequestHandler _
    Inherits WorkflowRequestHandler(Of ValidateHardwareStationTokenRequest, ValidateHardwareStationTokenResponse)
'Usage
Dim instance As ValidateHardwareStationTokenRequestHandler
```

``` csharp
public sealed class ValidateHardwareStationTokenRequestHandler : WorkflowRequestHandler<ValidateHardwareStationTokenRequest, ValidateHardwareStationTokenResponse>
```

``` c++
public ref class ValidateHardwareStationTokenRequestHandler sealed : public WorkflowRequestHandler<ValidateHardwareStationTokenRequest^, ValidateHardwareStationTokenResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[ValidateHardwareStationTokenRequest](validatehardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [ValidateHardwareStationTokenResponse](validatehardwarestationtokenresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateHardwareStationTokenRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

