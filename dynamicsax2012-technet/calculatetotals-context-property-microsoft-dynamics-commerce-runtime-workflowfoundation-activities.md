---
title: CalculateTotals.Context Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Context
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.calculatetotals.context(v=AX.60)
ms:contentKeyID: 65319097
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Context
dev_langs:
- CSharp
- C++
- VB
---

# Context Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
<RequiredArgumentAttribute> _
Public Property Context As InArgument(Of RequestContext)
    Get
    Set
'Usage
Dim instance As CalculateTotals
Dim value As InArgument(Of RequestContext)

value = instance.Context

instance.Context = value
```

``` csharp
[RequiredArgumentAttribute]
public InArgument<RequestContext> Context { get; set; }
```

``` c++
[RequiredArgumentAttribute]
public:
property InArgument<RequestContext^>^ Context {
    InArgument<RequestContext^>^ get ();
    void set (InArgument<RequestContext^>^ value);
}
```

#### Property Value

Type: InArgument\<[RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns InArgument.  

## See Also

#### Reference

[CalculateTotals Class](calculatetotals-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

