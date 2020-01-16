---
title: ICommerceRuntimeConfiguration.DatabaseProvider Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DatabaseProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.DatabaseProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.databaseprovider(v=AX.60)
ms:contentKeyID: 65318019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.DatabaseProvider
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseProvider Property

Gets the database provider instance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DatabaseProvider As IDatabaseProvider
    Get
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As IDatabaseProvider

value = instance.DatabaseProvider
```

``` csharp
IDatabaseProvider DatabaseProvider { get; }
```

``` c++
property IDatabaseProvider^ DatabaseProvider {
    IDatabaseProvider^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

