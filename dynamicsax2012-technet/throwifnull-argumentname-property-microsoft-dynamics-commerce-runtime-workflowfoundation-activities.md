---
title: ThrowIfNull.ArgumentName Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: ArgumentName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ThrowIfNull.ArgumentName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.throwifnull.argumentname(v=AX.60)
ms:contentKeyID: 65321227
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ThrowIfNull.ArgumentName
dev_langs:
- CSharp
- C++
- VB
---

# ArgumentName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets argument name to provide in exception.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property ArgumentName As InArgument(Of String)
    Get
    Set
'Usage
Dim instance As ThrowIfNull
Dim value As InArgument(Of String)

value = instance.ArgumentName

instance.ArgumentName = value
```

``` csharp
public InArgument<string> ArgumentName { get; set; }
```

``` c++
public:
property InArgument<String^>^ ArgumentName {
    InArgument<String^>^ get ();
    void set (InArgument<String^>^ value);
}
```

#### Property Value

Type: InArgument\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[ThrowIfNull Class](throwifnull-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

