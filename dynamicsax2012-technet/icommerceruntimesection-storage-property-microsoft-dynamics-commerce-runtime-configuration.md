---
title: ICommerceRuntimeSection.Storage Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Storage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Storage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.storage(v=AX.60)
ms:contentKeyID: 65320355
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Storage
dev_langs:
- CSharp
- C++
- VB
---

# Storage Property

Gets the storage element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Storage As IStorageElement
    Get
'Usage
Dim instance As ICommerceRuntimeSection
Dim value As IStorageElement

value = instance.Storage
```

``` csharp
IStorageElement Storage { get; }
```

``` c++
property IStorageElement^ Storage {
    IStorageElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.IStorageElement](istorageelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [IStorageElement](istorageelement-interface-microsoft-dynamics-commerce-runtime-configuration.md).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

