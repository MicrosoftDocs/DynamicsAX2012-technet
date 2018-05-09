---
title: RequestHandlerActivity(TResponse).RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1.RequestContext
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn990518(v=AX.60)
ms:contentKeyID: 65321458
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1.RequestContext
dev_langs:
- CSharp
- C++
- VB
---

# RequestContext Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property RequestContext As InOutArgument(Of RequestContext)
    Get
    Set
'Usage
Dim instance As RequestHandlerActivity
Dim value As InOutArgument(Of RequestContext)

value = instance.RequestContext

instance.RequestContext = value
```

``` csharp
public InOutArgument<RequestContext> RequestContext { get; set; }
```

``` c++
public:
property InOutArgument<RequestContext^>^ RequestContext {
    InOutArgument<RequestContext^>^ get ();
    void set (InOutArgument<RequestContext^>^ value);
}
```

#### Property Value

Type: InOutArgument\<[RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[RequestHandlerActivity\<TResponse\> Class](requesthandleractivity-tresponse-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

