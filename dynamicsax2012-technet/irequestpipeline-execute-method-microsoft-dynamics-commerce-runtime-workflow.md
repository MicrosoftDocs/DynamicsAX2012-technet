---
title: IRequestPipeline.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestPipeline.Execute(Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler,Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.irequestpipeline.execute(v=AX.60)
ms:contentKeyID: 65322310
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestPipeline.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Execute ( _
    handler As IRequestHandler, _
    request As Request _
) As Response
'Usage
Dim instance As IRequestPipeline
Dim handler As IRequestHandler
Dim request As Request
Dim returnValue As Response

returnValue = instance.Execute(handler, _
    request)
```

``` csharp
Response Execute(
    IRequestHandler handler,
    Request request
)
```

``` c++
Response^ Execute(
    IRequestHandler^ handler, 
    Request^ request
)
```

#### Parameters

  - handler  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  

## See Also

#### Reference

[IRequestPipeline Interface](irequestpipeline-interface-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

