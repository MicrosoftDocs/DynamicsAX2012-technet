---
title: CommercePrincipal.AnonymousPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: AnonymousPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.AnonymousPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.anonymousprincipal(v=AX.60)
ms:contentKeyID: 62201743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.AnonymousPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# AnonymousPrincipal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the principal object representing an anonymous user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Shared ReadOnly Property AnonymousPrincipal As CommercePrincipal
    Get
'Usage
Dim value As CommercePrincipal

value = CommercePrincipal.AnonymousPrincipal
```

``` csharp
[DataMemberAttribute]
public static CommercePrincipal AnonymousPrincipal { get; }
```

``` c++
[DataMemberAttribute]
public:
static property CommercePrincipal^ AnonymousPrincipal {
    CommercePrincipal^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns [CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

