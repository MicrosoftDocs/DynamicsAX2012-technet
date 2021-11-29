---
title: TaxCode.IsStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: IsStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.IsStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.isstorecurrency(v=AX.60)
ms:contentKeyID: 49821769
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.IsStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# IsStoreCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Whether or not a given TaxCode is in the Store Currency

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property IsStoreCurrency As Boolean
    Get
'Usage
Dim instance As TaxCode
Dim value As Boolean

value = instance.IsStoreCurrency
```

``` csharp
public bool IsStoreCurrency { get; }
```

``` c++
public:
property bool IsStoreCurrency {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if this instance is store currency; otherwise, false.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

