---
title: PriceCheckRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: PriceCheckRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.pricecheckrequesthandler(v=AX.60)
ms:contentKeyID: 62209326
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# PriceCheckRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates the workflow required to get price check information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class PriceCheckRequestHandler _
    Inherits WorkflowRequestHandler(Of PriceCheckRequest, PriceCheckResponse)
'Usage
Dim instance As PriceCheckRequestHandler
```

``` csharp
public sealed class PriceCheckRequestHandler : WorkflowRequestHandler<PriceCheckRequest, PriceCheckResponse>
```

``` c++
public ref class PriceCheckRequestHandler sealed : public WorkflowRequestHandler<PriceCheckRequest^, PriceCheckResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[PriceCheckRequest](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [PriceCheckResponse](pricecheckresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

