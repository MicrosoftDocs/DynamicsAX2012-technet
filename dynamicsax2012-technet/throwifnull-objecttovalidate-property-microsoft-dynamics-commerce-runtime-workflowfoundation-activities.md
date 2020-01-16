---
title: ThrowIfNull.ObjectToValidate Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: ObjectToValidate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ThrowIfNull.ObjectToValidate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.throwifnull.objecttovalidate(v=AX.60)
ms:contentKeyID: 65319092
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ThrowIfNull.ObjectToValidate
dev_langs:
- CSharp
- C++
- VB
---

# ObjectToValidate Property

Gets or sets object to validate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property ObjectToValidate As InArgument(Of Object)
    Get
    Set
'Usage
Dim instance As ThrowIfNull
Dim value As InArgument(Of Object)

value = instance.ObjectToValidate

instance.ObjectToValidate = value
```

``` csharp
public InArgument<Object> ObjectToValidate { get; set; }
```

``` c++
public:
property InArgument<Object^>^ ObjectToValidate {
    InArgument<Object^>^ get ();
    void set (InArgument<Object^>^ value);
}
```

#### Property Value

Type: InArgument\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[ThrowIfNull Class](throwifnull-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

