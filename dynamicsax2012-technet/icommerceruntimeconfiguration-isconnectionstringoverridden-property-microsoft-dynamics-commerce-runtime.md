---
title: ICommerceRuntimeConfiguration.IsConnectionStringOverridden Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsConnectionStringOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.IsConnectionStringOverridden
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.isconnectionstringoverridden(v=AX.60)
ms:contentKeyID: 65318943
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.IsConnectionStringOverridden
dev_langs:
- CSharp
- C++
- VB
---

# IsConnectionStringOverridden Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the specified connection string has been overridden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property IsConnectionStringOverridden As Boolean
    Get
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As Boolean

value = instance.IsConnectionStringOverridden
```

``` csharp
bool IsConnectionStringOverridden { get; }
```

``` c++
property bool IsConnectionStringOverridden {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

