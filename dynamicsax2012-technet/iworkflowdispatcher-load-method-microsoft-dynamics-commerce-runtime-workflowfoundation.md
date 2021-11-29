---
title: IWorkflowDispatcher.Load Method  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: Load Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.IWorkflowDispatcher.Load(Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.iworkflowdispatcher.load(v=AX.60)
ms:contentKeyID: 62215111
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.IWorkflowDispatcher.Load
dev_langs:
- CSharp
- C++
- VB
---

# Load Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads workflow from specified location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Function Load ( _
    location As WorkflowLocation _
) As Activity
'Usage
Dim instance As IWorkflowDispatcher
Dim location As WorkflowLocation
Dim returnValue As Activity

returnValue = instance.Load(location)
```

``` csharp
Activity Load(
    WorkflowLocation location
)
```

``` c++
Activity^ Load(
    WorkflowLocation^ location
)
```

#### Parameters

  - location  
    Type: [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)  

#### Return Value

Type: Activity  
Loaded workflow.  

## See Also

#### Reference

[IWorkflowDispatcher Interface](iworkflowdispatcher-interface-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

