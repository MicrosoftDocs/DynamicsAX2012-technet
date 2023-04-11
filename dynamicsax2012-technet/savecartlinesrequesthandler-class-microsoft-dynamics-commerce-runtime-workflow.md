---
title: SaveCartLinesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveCartLinesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveCartLinesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savecartlinesrequesthandler(v=AX.60)
ms:contentKeyID: 62211209
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveCartLinesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveCartLinesRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves a cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SaveCartLinesRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveCartLinesRequest, SaveCartLinesResponse)
'Usage
Dim instance As SaveCartLinesRequestHandler
```

``` csharp
public sealed class SaveCartLinesRequestHandler : WorkflowRequestHandler<SaveCartLinesRequest, SaveCartLinesResponse>
```

``` c++
public ref class SaveCartLinesRequestHandler sealed : public WorkflowRequestHandler<SaveCartLinesRequest^, SaveCartLinesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveCartLinesRequest](savecartlinesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveCartLinesResponse](savecartlinesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveCartLinesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

