---
title: TaxCode.TaxGroupRounding Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxGroupRounding Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxGroupRounding
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxgrouprounding(v=AX.60)
ms:contentKeyID: 49839172
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxGroupRounding
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroupRounding Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Whether or not this code should be rounded at the Tax Group scope.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxGroupRounding As Boolean
    Get
    Set
'Usage
Dim instance As TaxCode
Dim value As Boolean

value = instance.TaxGroupRounding

instance.TaxGroupRounding = value
```

``` csharp
public bool TaxGroupRounding { get; set; }
```

``` c++
public:
property bool TaxGroupRounding {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

