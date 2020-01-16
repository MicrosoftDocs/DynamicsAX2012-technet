---
title: TypeCastActivity(TResult) Class (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: TypeCastActivity(TResult) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TypeCastActivity`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn988920(v=AX.60)
ms:contentKeyID: 65318370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TypeCastActivity`1
dev_langs:
- CSharp
- C++
- VB
---

# TypeCastActivity(TResult) Class

Generic activity to cast object to specific type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class TypeCastActivity(Of TResult) _
    Inherits CodeActivity(Of TResult)
'Usage
Dim instance As TypeCastActivity(Of TResult)
```

``` csharp
public sealed class TypeCastActivity<TResult> : CodeActivity<TResult>
```

``` c++
generic<typename TResult>
public ref class TypeCastActivity sealed : public CodeActivity<TResult>
```

#### Type Parameters

  - TResult

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Activity  
    ActivityWithResult  
      Activity\<TResult\>  
        CodeActivity\<TResult\>  
          Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TypeCastActivity\<TResult\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

