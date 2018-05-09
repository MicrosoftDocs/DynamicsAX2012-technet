---
title: WorkflowFoundationConfiguration.LoadType Method  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: LoadType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.LoadType(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowfoundationconfiguration.loadtype(v=AX.60)
ms:contentKeyID: 62213772
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowFoundationConfiguration.LoadType
dev_langs:
- CSharp
- C++
- VB
---

# LoadType Method

Gets the Type with the specified name, performing a case-sensitive search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function LoadType ( _
    typeName As String _
) As Type
'Usage
Dim typeName As String
Dim returnValue As Type

returnValue = WorkflowFoundationConfiguration.LoadType(typeName)
```

``` csharp
protected static Type LoadType(
    string typeName
)
```

``` c++
protected:
static Type^ LoadType(
    String^ typeName
)
```

#### Parameters

  - typeName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))  
The type with the specified name.  

## Remarks

Throws [ConfigurationErrorsException](https://technet.microsoft.com/en-us/library/ms134182\(v=ax.60\)) if type not found.

## See Also

#### Reference

[WorkflowFoundationConfiguration Class](workflowfoundationconfiguration-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

