---
title: ValidateUpdateCartRequest.RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ValidateUpdateCartRequest.RequestContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.validateupdatecartrequest.requestcontext(v=AX.60)
ms:contentKeyID: 65321818
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ValidateUpdateCartRequest.RequestContext
dev_langs:
- CSharp
- C++
- VB
---

# RequestContext Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets request context argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property RequestContext As InArgument(Of RequestContext)
    Get
    Set
'Usage
Dim instance As ValidateUpdateCartRequest
Dim value As InArgument(Of RequestContext)

value = instance.RequestContext

instance.RequestContext = value
```

``` csharp
public InArgument<RequestContext> RequestContext { get; set; }
```

``` c++
public:
property InArgument<RequestContext^>^ RequestContext {
    InArgument<RequestContext^>^ get ();
    void set (InArgument<RequestContext^>^ value);
}
```

#### Property Value

Type: InArgument\<[RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns InArgument.  

## See Also

#### Reference

[ValidateUpdateCartRequest Class](validateupdatecartrequest-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

