---
title: TaxCodeProvider.Identifier Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Identifier Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.Identifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.identifier(v=AX.60)
ms:contentKeyID: 49848227
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.Identifier
dev_langs:
- CSharp
- C++
- VB
---

# Identifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property Identifier As String
    Get
    Protected Set
'Usage
Dim instance As TaxCodeProvider
Dim value As String

value = instance.Identifier

instance.Identifier = value
```

``` csharp
public string Identifier { get; protected set; }
```

``` c++
public:
property String^ Identifier {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The identifier.  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

