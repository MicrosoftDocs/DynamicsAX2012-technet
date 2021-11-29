---
title: WorkflowFoundationConfiguration.WorkflowMappings Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: WorkflowMappings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.WorkflowMappings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationconfiguration.workflowmappings(v=AX.60)
ms:contentKeyID: 62206518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.WorkflowMappings
dev_langs:
- CSharp
- C++
- VB
---

# WorkflowMappings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets workflow mappings collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Property WorkflowMappings As Dictionary(Of Type, WorkflowLocation)
    Get
    Private Set
'Usage
Dim instance As WorkflowFoundationConfiguration
Dim value As Dictionary(Of Type, WorkflowLocation)

value = instance.WorkflowMappings
```

``` csharp
public Dictionary<Type, WorkflowLocation> WorkflowMappings { get; private set; }
```

``` c++
public:
property Dictionary<Type^, WorkflowLocation^>^ WorkflowMappings {
    Dictionary<Type^, WorkflowLocation^>^ get ();
    private: void set (Dictionary<Type^, WorkflowLocation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\)), [WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[WorkflowFoundationConfiguration Class](workflowfoundationconfiguration-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

