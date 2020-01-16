---
title: CommerceRuntimeConfiguration.Storage Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Storage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.Storage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.storage(v=AX.60)
ms:contentKeyID: 65322993
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.Storage
dev_langs:
- CSharp
- C++
- VB
---

# Storage Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property Storage As IStorageElement
    Get
    Private Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As IStorageElement

value = instance.Storage
```

``` csharp
public IStorageElement Storage { get; private set; }
```

``` c++
public:
virtual property IStorageElement^ Storage {
    IStorageElement^ get () sealed;
    private: void set (IStorageElement^ value) sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.IStorageElement](istorageelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  

#### Implements

[ICommerceRuntimeConfiguration.Storage](icommerceruntimeconfiguration-storage-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

