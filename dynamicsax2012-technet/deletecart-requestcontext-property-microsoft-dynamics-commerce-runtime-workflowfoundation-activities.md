---
title: DeleteCart.RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteCart.RequestContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.deletecart.requestcontext(v=AX.60)
ms:contentKeyID: 65322593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteCart.RequestContext
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
Public Property RequestContext As InArgument(Of RequestContext)
    Get
    Set
'Usage
Dim instance As DeleteCart
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

[DeleteCart Class](deletecart-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

