---
title: ValidateUpdateCartRequest.Request Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Request Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ValidateUpdateCartRequest.Request
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.validateupdatecartrequest.request(v=AX.60)
ms:contentKeyID: 65316376
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.ValidateUpdateCartRequest.Request
dev_langs:
- CSharp
- C++
- VB
---

# Request Property

Gets or sets request argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property Request As InArgument(Of SaveCartRequest)
    Get
    Set
'Usage
Dim instance As ValidateUpdateCartRequest
Dim value As InArgument(Of SaveCartRequest)

value = instance.Request

instance.Request = value
```

``` csharp
public InArgument<SaveCartRequest> Request { get; set; }
```

``` c++
public:
property InArgument<SaveCartRequest^>^ Request {
    InArgument<SaveCartRequest^>^ get ();
    void set (InArgument<SaveCartRequest^>^ value);
}
```

#### Property Value

Type: InArgument\<[SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
Returns InArgument.  

## See Also

#### Reference

[ValidateUpdateCartRequest Class](validateupdatecartrequest-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

