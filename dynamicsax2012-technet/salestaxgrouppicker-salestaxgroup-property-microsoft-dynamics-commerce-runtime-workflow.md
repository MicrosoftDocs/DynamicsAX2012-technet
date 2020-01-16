---
title: SalesTaxGroupPicker.SalesTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SalesTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Workflow.SalesTaxGroupPicker.SalesTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.salestaxgrouppicker.salestaxgroup(v=AX.60)
ms:contentKeyID: 62206301
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SalesTaxGroupPicker.SalesTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroup Property

Gets the SalesTaxGroup based on business rules.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SalesTaxGroup As String
    Get
'Usage
Dim instance As SalesTaxGroupPicker
Dim value As String

value = instance.SalesTaxGroup
```

``` csharp
public string SalesTaxGroup { get; }
```

``` c++
public:
property String^ SalesTaxGroup {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The SalesTaxGroup setting.  

## See Also

#### Reference

[SalesTaxGroupPicker Class](salestaxgrouppicker-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

