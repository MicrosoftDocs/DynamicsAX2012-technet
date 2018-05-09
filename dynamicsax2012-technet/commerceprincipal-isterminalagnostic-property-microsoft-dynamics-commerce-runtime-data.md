---
title: CommercePrincipal.IsTerminalAgnostic Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsTerminalAgnostic Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsTerminalAgnostic
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.isterminalagnostic(v=AX.60)
ms:contentKeyID: 62207980
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsTerminalAgnostic
dev_langs:
- CSharp
- C++
- VB
---

# IsTerminalAgnostic Property

Gets a value indicating whether terminal is agnostic.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsTerminalAgnostic As Boolean
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As Boolean

value = instance.IsTerminalAgnostic
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsTerminalAgnostic { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsTerminalAgnostic {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

