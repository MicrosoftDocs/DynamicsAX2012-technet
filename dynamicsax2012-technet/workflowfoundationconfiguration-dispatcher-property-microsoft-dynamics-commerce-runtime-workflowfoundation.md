---
title: WorkflowFoundationConfiguration.Dispatcher Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: Dispatcher Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.Dispatcher
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationconfiguration.dispatcher(v=AX.60)
ms:contentKeyID: 62215249
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.Dispatcher
dev_langs:
- CSharp
- C++
- VB
---

# Dispatcher Property

Gets instance of workflow dispatcher.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Property Dispatcher As IWorkflowDispatcher
    Get
    Private Set
'Usage
Dim instance As WorkflowFoundationConfiguration
Dim value As IWorkflowDispatcher

value = instance.Dispatcher
```

``` csharp
public IWorkflowDispatcher Dispatcher { get; private set; }
```

``` c++
public:
property IWorkflowDispatcher^ Dispatcher {
    IWorkflowDispatcher^ get ();
    private: void set (IWorkflowDispatcher^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.IWorkflowDispatcher](iworkflowdispatcher-interface-microsoft-dynamics-commerce-runtime-workflowfoundation.md)  
Returns [IWorkflowDispatcher](iworkflowdispatcher-interface-microsoft-dynamics-commerce-runtime-workflowfoundation.md).  

## See Also

#### Reference

[WorkflowFoundationConfiguration Class](workflowfoundationconfiguration-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

