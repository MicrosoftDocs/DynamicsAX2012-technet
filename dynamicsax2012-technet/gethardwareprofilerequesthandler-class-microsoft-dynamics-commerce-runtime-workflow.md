---
title: GetHardwareProfileRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetHardwareProfileRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetHardwareProfileRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.gethardwareprofilerequesthandler(v=AX.60)
ms:contentKeyID: 62213453
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetHardwareProfileRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetHardwareProfileRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Request handler to get the hardware profiles.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class GetHardwareProfileRequestHandler _
    Inherits WorkflowRequestHandler(Of GetHardwareProfileRequest, GetHardwareProfileResponse)
'Usage
Dim instance As GetHardwareProfileRequestHandler
```

``` csharp
public sealed class GetHardwareProfileRequestHandler : WorkflowRequestHandler<GetHardwareProfileRequest, GetHardwareProfileResponse>
```

``` c++
public ref class GetHardwareProfileRequestHandler sealed : public WorkflowRequestHandler<GetHardwareProfileRequest^, GetHardwareProfileResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetHardwareProfileRequest](gethardwareprofilerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetHardwareProfileResponse](gethardwareprofileresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetHardwareProfileRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

