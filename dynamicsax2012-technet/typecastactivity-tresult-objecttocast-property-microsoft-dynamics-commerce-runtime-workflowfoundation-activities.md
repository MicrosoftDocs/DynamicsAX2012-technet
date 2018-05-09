---
title: TypeCastActivity(TResult).ObjectToCast Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: ObjectToCast Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TypeCastActivity`1.ObjectToCast
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn967740(v=AX.60)
ms:contentKeyID: 65319610
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TypeCastActivity`1.ObjectToCast
dev_langs:
- CSharp
- C++
- VB
---

# ObjectToCast Property

Gets or sets object to cast.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property ObjectToCast As InArgument(Of Object)
    Get
    Set
'Usage
Dim instance As TypeCastActivity
Dim value As InArgument(Of Object)

value = instance.ObjectToCast

instance.ObjectToCast = value
```

``` csharp
public InArgument<Object> ObjectToCast { get; set; }
```

``` c++
public:
property InArgument<Object^>^ ObjectToCast {
    InArgument<Object^>^ get ();
    void set (InArgument<Object^>^ value);
}
```

#### Property Value

Type: InArgument\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[TypeCastActivity\<TResult\> Class](typecastactivity-tresult-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

