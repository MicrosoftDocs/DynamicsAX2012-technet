---
title: WorkflowLocation.Equals Method (WorkflowLocation) (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: Equals Method (WorkflowLocation)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation.Equals(Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowlocation.equals(v=AX.60)
ms:contentKeyID: 62213541
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (WorkflowLocation)

Determines whether the specified [WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md) is equal to this instance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As WorkflowLocation _
) As Boolean
'Usage
Dim instance As WorkflowLocation
Dim other As WorkflowLocation
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    WorkflowLocation other
)
```

``` c++
public:
virtual bool Equals(
    WorkflowLocation^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the specified [WorkflowLocation](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md) is equal to this instance; otherwise, false.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[WorkflowLocation Class](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Equals Overload](workflowlocation-equals-method-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

