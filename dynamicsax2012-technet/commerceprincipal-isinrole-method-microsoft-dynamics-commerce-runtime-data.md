---
title: CommercePrincipal.IsInRole Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsInRole Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsInRole(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.isinrole(v=AX.60)
ms:contentKeyID: 65322816
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsInRole
dev_langs:
- CSharp
- C++
- VB
---

# IsInRole Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsInRole ( _
    role As String _
) As Boolean
'Usage
Dim instance As CommercePrincipal
Dim role As String
Dim returnValue As Boolean

returnValue = instance.IsInRole(role)
```

``` csharp
public bool IsInRole(
    string role
)
```

``` c++
public:
virtual bool IsInRole(
    String^ role
) sealed
```

#### Parameters

  - role  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Implements

[IPrincipal.IsInRole(String)](https://technet.microsoft.com/en-us/library/3cdewxwy\(v=ax.60\))  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

