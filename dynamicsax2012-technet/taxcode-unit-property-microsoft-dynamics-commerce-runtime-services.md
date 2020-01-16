---
title: TaxCode.Unit Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Unit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Unit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.unit(v=AX.60)
ms:contentKeyID: 49841382
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Unit
dev_langs:
- CSharp
- C++
- VB
---

# Unit Property

Unit for calculating per-unit amounts

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property Unit As String
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As String

value = instance.Unit

instance.Unit = value
```

``` csharp
public string Unit { get; protected set; }
```

``` c++
public:
property String^ Unit {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

