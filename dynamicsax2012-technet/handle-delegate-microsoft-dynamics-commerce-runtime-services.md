---
title: Handle Delegate (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Handle Delegate
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Handle
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.handle(v=AX.60)
ms:contentKeyID: 49836482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Handle
dev_langs:
- CSharp
- C++
- VB
---

# Handle Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates the predicates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub Handle ( _
    address As Address, _
    predicates As IDictionary(Of String, String) _
)
'Usage
Dim instance As New Handle(AddressOf HandlerMethod)
```

``` csharp
public delegate void Handle(
    Address address,
    IDictionary<string, string> predicates
)
```

``` c++
public delegate void Handle(
    Address^ address, 
    IDictionary<String^, String^>^ predicates
)
```

#### Parameters

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - predicates  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

