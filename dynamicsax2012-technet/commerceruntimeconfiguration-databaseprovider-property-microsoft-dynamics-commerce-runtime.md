---
title: CommerceRuntimeConfiguration.DatabaseProvider Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DatabaseProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.DatabaseProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.databaseprovider(v=AX.60)
ms:contentKeyID: 65320109
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.DatabaseProvider
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseProvider Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property DatabaseProvider As IDatabaseProvider
    Get
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As IDatabaseProvider

value = instance.DatabaseProvider
```

``` csharp
public IDatabaseProvider DatabaseProvider { get; }
```

``` c++
public:
virtual property IDatabaseProvider^ DatabaseProvider {
    IDatabaseProvider^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[ICommerceRuntimeConfiguration.DatabaseProvider](icommerceruntimeconfiguration-databaseprovider-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

