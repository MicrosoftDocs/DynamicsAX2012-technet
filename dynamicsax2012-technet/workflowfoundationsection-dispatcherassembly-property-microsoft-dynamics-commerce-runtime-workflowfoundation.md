---
title: WorkflowFoundationSection.DispatcherAssembly Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: DispatcherAssembly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.DispatcherAssembly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationsection.dispatcherassembly(v=AX.60)
ms:contentKeyID: 62207094
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.DispatcherAssembly
dev_langs:
- CSharp
- C++
- VB
---

# DispatcherAssembly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets assembly name to load dispatcher from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("dispatcherAssembly", DefaultValue := "", IsRequired := True)> _
Public ReadOnly Property DispatcherAssembly As String
    Get
'Usage
Dim instance As WorkflowFoundationSection
Dim value As String

value = instance.DispatcherAssembly
```

``` csharp
[ConfigurationPropertyAttribute("dispatcherAssembly", DefaultValue = "", IsRequired = true)]
public string DispatcherAssembly { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"dispatcherAssembly", DefaultValue = L"", IsRequired = true)]
public:
property String^ DispatcherAssembly {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Has to be fully qualified name.

## See Also

#### Reference

[WorkflowFoundationSection Class](workflowfoundationsection-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

