---
title: PipelineRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PipelineRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler,Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.pipelinerequesthandler.execute(v=AX.60)
ms:contentKeyID: 65322162
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PipelineRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes each step in the process including the pre and post steps and the underlying handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    handler As IRequestHandler, _
    request As Request _
) As Response
'Usage
Dim instance As PipelineRequestHandler
Dim handler As IRequestHandler
Dim request As Request
Dim returnValue As Response

returnValue = instance.Execute(handler, _
    request)
```

``` csharp
public Response Execute(
    IRequestHandler handler,
    Request request
)
```

``` c++
public:
virtual Response^ Execute(
    IRequestHandler^ handler, 
    Request^ request
) sealed
```

#### Parameters

  - handler  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
The outgoing response message.  

#### Implements

[IRequestPipeline.Execute(IRequestHandler, Request)](irequestpipeline-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[PipelineRequestHandler Class](pipelinerequesthandler-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

