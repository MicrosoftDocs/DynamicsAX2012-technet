---
title: WorkflowFoundationSection.WorkflowMappings Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: WorkflowMappings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.WorkflowMappings
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationsection.workflowmappings(v=AX.60)
ms:contentKeyID: 62213947
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.WorkflowMappings
dev_langs:
- CSharp
- C++
- VB
---

# WorkflowMappings Property

Gets the workflow mappings collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("", IsDefaultCollection := True)> _
Public ReadOnly Property WorkflowMappings As NameValueConfigurationCollection
    Get
'Usage
Dim instance As WorkflowFoundationSection
Dim value As NameValueConfigurationCollection

value = instance.WorkflowMappings
```

``` csharp
[ConfigurationPropertyAttribute("", IsDefaultCollection = true)]
public NameValueConfigurationCollection WorkflowMappings { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"", IsDefaultCollection = true)]
public:
property NameValueConfigurationCollection^ WorkflowMappings {
    NameValueConfigurationCollection^ get ();
}
```

#### Property Value

Type: [System.Configuration.NameValueConfigurationCollection](https://technet.microsoft.com/en-us/library/ms134603\(v=ax.60\))  
Returns [NameValueConfigurationCollection](https://technet.microsoft.com/en-us/library/ms134603\(v=ax.60\)).  

## See Also

#### Reference

[WorkflowFoundationSection Class](workflowfoundationsection-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

