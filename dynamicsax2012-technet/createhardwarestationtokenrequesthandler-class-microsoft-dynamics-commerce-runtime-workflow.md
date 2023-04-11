---
title: CreateHardwareStationTokenRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateHardwareStationTokenRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateHardwareStationTokenRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.createhardwarestationtokenrequesthandler(v=AX.60)
ms:contentKeyID: 62211250
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateHardwareStationTokenRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# CreateHardwareStationTokenRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow for creating a hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateHardwareStationTokenRequestHandler _
    Inherits WorkflowRequestHandler(Of CreateHardwareStationTokenRequest, CreateHardwareStationTokenResponse)
'Usage
Dim instance As CreateHardwareStationTokenRequestHandler
```

``` csharp
public sealed class CreateHardwareStationTokenRequestHandler : WorkflowRequestHandler<CreateHardwareStationTokenRequest, CreateHardwareStationTokenResponse>
```

``` c++
public ref class CreateHardwareStationTokenRequestHandler sealed : public WorkflowRequestHandler<CreateHardwareStationTokenRequest^, CreateHardwareStationTokenResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[CreateHardwareStationTokenRequest](createhardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [CreateHardwareStationTokenResponse](createhardwarestationtokenresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateHardwareStationTokenRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

