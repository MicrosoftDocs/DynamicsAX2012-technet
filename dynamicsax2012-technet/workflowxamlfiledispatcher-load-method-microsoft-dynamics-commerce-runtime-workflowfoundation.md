---
title: WorkflowXamlFileDispatcher.Load Method  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: Load Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowXamlFileDispatcher.Load(Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowxamlfiledispatcher.load(v=AX.60)
ms:contentKeyID: 62212111
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowXamlFileDispatcher.Load
dev_langs:
- CSharp
- C++
- VB
---

# Load Method

Loads workflow from xaml file.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Function Load ( _
    location As WorkflowLocation _
) As Activity
'Usage
Dim instance As WorkflowXamlFileDispatcher
Dim location As WorkflowLocation
Dim returnValue As Activity

returnValue = instance.Load(location)
```

``` csharp
public Activity Load(
    WorkflowLocation location
)
```

``` c++
public:
virtual Activity^ Load(
    WorkflowLocation^ location
) sealed
```

#### Parameters

  - location  
    Type: [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)  

#### Return Value

Type: Activity  
Workflow definition instance loaded from xaml.  

#### Implements

[IWorkflowDispatcher.Load(WorkflowLocation)](iworkflowdispatcher-load-method-microsoft-dynamics-commerce-runtime-workflowfoundation.md)  

## See Also

#### Reference

[WorkflowXamlFileDispatcher Class](workflowxamlfiledispatcher-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

