---
title: TaxCode.Exempt Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Exempt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Exempt
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.exempt(v=AX.60)
ms:contentKeyID: 49840388
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Exempt
dev_langs:
- CSharp
- C++
- VB
---

# Exempt Property

Whether or not this tax is exempt

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property Exempt As Boolean
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As Boolean

value = instance.Exempt

instance.Exempt = value
```

``` csharp
public bool Exempt { get; protected set; }
```

``` c++
public:
property bool Exempt {
    bool get ();
    protected: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

