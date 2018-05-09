---
title: DeleteCart.Response Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Response Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteCart.Response
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.deletecart.response(v=AX.60)
ms:contentKeyID: 65322628
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteCart.Response
dev_langs:
- CSharp
- C++
- VB
---

# Response Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property Response As OutArgument(Of Response)
    Get
    Set
'Usage
Dim instance As DeleteCart
Dim value As OutArgument(Of Response)

value = instance.Response

instance.Response = value
```

``` csharp
public OutArgument<Response> Response { get; set; }
```

``` c++
public:
property OutArgument<Response^>^ Response {
    OutArgument<Response^>^ get ();
    void set (OutArgument<Response^>^ value);
}
```

#### Property Value

Type: OutArgument\<[Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
Returns OutArgument.  

## See Also

#### Reference

[DeleteCart Class](deletecart-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

