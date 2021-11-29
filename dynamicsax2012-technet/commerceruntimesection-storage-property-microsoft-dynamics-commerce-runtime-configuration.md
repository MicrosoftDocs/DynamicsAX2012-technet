---
title: CommerceRuntimeSection.Storage Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Storage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Storage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.storage(v=AX.60)
ms:contentKeyID: 62213761
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Storage
dev_langs:
- CSharp
- C++
- VB
---

# Storage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the storage element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Storage As IStorageElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As IStorageElement

value = instance.Storage
```

``` csharp
public IStorageElement Storage { get; }
```

``` c++
public:
virtual property IStorageElement^ Storage {
    IStorageElement^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.IStorageElement](istorageelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [StorageElement](storageelement-class-microsoft-dynamics-commerce-runtime-configuration.md).  

#### Implements

[ICommerceRuntimeSection.Storage](icommerceruntimesection-storage-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

