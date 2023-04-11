---
title: WorkflowFoundationSection.StoragePath Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: StoragePath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.StoragePath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationsection.storagepath(v=AX.60)
ms:contentKeyID: 62214085
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationSection.StoragePath
dev_langs:
- CSharp
- C++
- VB
---

# StoragePath Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets base location of workflows.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("storagePath", DefaultValue := "", IsRequired := True)> _
Public ReadOnly Property StoragePath As String
    Get
'Usage
Dim instance As WorkflowFoundationSection
Dim value As String

value = instance.StoragePath
```

``` csharp
[ConfigurationPropertyAttribute("storagePath", DefaultValue = "", IsRequired = true)]
public string StoragePath { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"storagePath", DefaultValue = L"", IsRequired = true)]
public:
property String^ StoragePath {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

For example can be folder path or database name.

## See Also

#### Reference

[WorkflowFoundationSection Class](workflowfoundationsection-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

