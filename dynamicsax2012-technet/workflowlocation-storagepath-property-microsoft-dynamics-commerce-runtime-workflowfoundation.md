---
title: WorkflowLocation.StoragePath Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation)
TOCTitle: StoragePath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation.StoragePath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.workflowlocation.storagepath(v=AX.60)
ms:contentKeyID: 62215248
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.WorkflowLocation.StoragePath
dev_langs:
- CSharp
- C++
- VB
---

# StoragePath Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets workflow storage location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.dll)

## Syntax

``` vb
'Declaration
Public Property StoragePath As String
    Get
    Set
'Usage
Dim instance As WorkflowLocation
Dim value As String

value = instance.StoragePath

instance.StoragePath = value
```

``` csharp
public string StoragePath { get; set; }
```

``` c++
public:
property String^ StoragePath {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

For example can be folder path or database name.

## See Also

#### Reference

[WorkflowLocation Class](workflowlocation-class-microsoft-dynamics-commerce-runtime-workflowfoundation.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-namespace.md)

