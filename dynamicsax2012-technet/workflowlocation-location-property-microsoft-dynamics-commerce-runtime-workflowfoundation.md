---
title: WorkflowLocation.Location Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: Location Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation.Location
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowlocation.location(v=AX.60)
ms:contentKeyID: 62209185
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation.Location
dev_langs:
- CSharp
- C++
- VB
---

# Location Property

Gets or sets location of specific workflow.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Property Location As String
    Get
    Set
'Usage
Dim instance As WorkflowLocation
Dim value As String

value = instance.Location

instance.Location = value
```

``` csharp
public string Location { get; set; }
```

``` c++
public:
property String^ Location {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

For example file name or row id in table.

## See Also

#### Reference

[WorkflowLocation Class](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

