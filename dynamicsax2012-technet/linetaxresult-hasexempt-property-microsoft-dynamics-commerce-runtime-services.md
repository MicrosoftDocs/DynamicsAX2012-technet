---
title: LineTaxResult.HasExempt Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: HasExempt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.HasExempt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.linetaxresult.hasexempt(v=AX.60)
ms:contentKeyID: 49856609
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.HasExempt
dev_langs:
- CSharp
- C++
- VB
---

# HasExempt Property

Gets or sets a value indicating whether this tax line is exempt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property HasExempt As Boolean
    Get
    Set
'Usage
Dim instance As LineTaxResult
Dim value As Boolean

value = instance.HasExempt

instance.HasExempt = value
```

``` csharp
public bool HasExempt { get; set; }
```

``` c++
public:
property bool HasExempt {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true this line tax result is exempt; otherwise, false.  

## See Also

#### Reference

[LineTaxResult Class](linetaxresult-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

