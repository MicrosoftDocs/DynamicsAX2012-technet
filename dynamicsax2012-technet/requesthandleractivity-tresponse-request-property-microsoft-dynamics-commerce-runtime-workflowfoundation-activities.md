---
title: RequestHandlerActivity(TResponse).Request Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Request Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1.Request
ms:mtpsurl: https://technet.microsoft.com/library/Dn987352(v=AX.60)
ms:contentKeyID: 65315908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1.Request
dev_langs:
- CSharp
- C++
- VB
---

# Request Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property Request As InArgument(Of Request)
    Get
    Set
'Usage
Dim instance As RequestHandlerActivity
Dim value As InArgument(Of Request)

value = instance.Request

instance.Request = value
```

``` csharp
public InArgument<Request> Request { get; set; }
```

``` c++
public:
property InArgument<Request^>^ Request {
    InArgument<Request^>^ get ();
    void set (InArgument<Request^>^ value);
}
```

#### Property Value

Type: InArgument\<[Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)\>  

## See Also

#### Reference

[RequestHandlerActivity\<TResponse\> Class](requesthandleractivity-tresponse-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

