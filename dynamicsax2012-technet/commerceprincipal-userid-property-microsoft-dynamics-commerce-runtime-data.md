---
title: CommercePrincipal.UserId Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.UserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.userid(v=AX.60)
ms:contentKeyID: 62211594
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.UserId
dev_langs:
- CSharp
- C++
- VB
---

# UserId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the user identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property UserId As String
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As String

value = instance.UserId
```

``` csharp
[DataMemberAttribute]
public string UserId { get; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UserId {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

