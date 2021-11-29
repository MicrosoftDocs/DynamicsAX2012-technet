---
title: CommerceRuntimeConfiguration.IsConnectionStringOverridden Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsConnectionStringOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.IsConnectionStringOverridden
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.isconnectionstringoverridden(v=AX.60)
ms:contentKeyID: 62212738
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.IsConnectionStringOverridden
dev_langs:
- CSharp
- C++
- VB
---

# IsConnectionStringOverridden Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the specified connection string has been overridden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property IsConnectionStringOverridden As Boolean
    Get
    Private Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As Boolean

value = instance.IsConnectionStringOverridden
```

``` csharp
public bool IsConnectionStringOverridden { get; private set; }
```

``` c++
public:
virtual property bool IsConnectionStringOverridden {
    bool get () sealed;
    private: void set (bool value) sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICommerceRuntimeConfiguration.IsConnectionStringOverridden](icommerceruntimeconfiguration-isconnectionstringoverridden-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

