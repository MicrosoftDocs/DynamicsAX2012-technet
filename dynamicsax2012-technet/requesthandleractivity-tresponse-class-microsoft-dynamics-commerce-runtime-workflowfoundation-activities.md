---
title: RequestHandlerActivity(TResponse) Class (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: RequestHandlerActivity(TResponse) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn966901(v=AX.60)
ms:contentKeyID: 65317763
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity`1
dev_langs:
- CSharp
- C++
- VB
---

# RequestHandlerActivity(TResponse) Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class RequestHandlerActivity(Of TResponse As Response) _
    Inherits CodeActivity(Of TResponse)
'Usage
Dim instance As RequestHandlerActivity(Of TResponse)
```

``` csharp
public sealed class RequestHandlerActivity<TResponse> : CodeActivity<TResponse>
where TResponse : Response
```

``` c++
generic<typename TResponse>
where TResponse : Response
public ref class RequestHandlerActivity sealed : public CodeActivity<TResponse>
```

#### Type Parameters

  - TResponse

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Activity  
    ActivityWithResult  
      Activity\<TResponse\>  
        CodeActivity\<TResponse\>  
          Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.RequestHandlerActivity\<TResponse\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

