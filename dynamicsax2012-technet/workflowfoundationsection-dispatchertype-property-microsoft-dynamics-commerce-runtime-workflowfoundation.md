---
title: WorkflowFoundationSection.DispatcherType Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: DispatcherType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.DispatcherType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationsection.dispatchertype(v=AX.60)
ms:contentKeyID: 62205197
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.DispatcherType
dev_langs:
- CSharp
- C++
- VB
---

# DispatcherType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets full name of the workflow dispatcher class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("dispatcherType", DefaultValue := "", IsRequired := True)> _
Public ReadOnly Property DispatcherType As String
    Get
'Usage
Dim instance As WorkflowFoundationSection
Dim value As String

value = instance.DispatcherType
```

``` csharp
[ConfigurationPropertyAttribute("dispatcherType", DefaultValue = "", IsRequired = true)]
public string DispatcherType { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"dispatcherType", DefaultValue = L"", IsRequired = true)]
public:
property String^ DispatcherType {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Has to implement the [IWorkflowDispatcher](iworkflowdispatcher-interface-microsoft-dynamics-commerce-runtime-workflowfoundation.md) interface.

## See Also

#### Reference

[WorkflowFoundationSection Class](workflowfoundationsection-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

