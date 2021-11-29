---
title: CommerceRuntimeSection.StorageElement Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: StorageElement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.StorageElement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.storageelement(v=AX.60)
ms:contentKeyID: 65320894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.StorageElement
dev_langs:
- CSharp
- C++
- VB
---

# StorageElement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("storage")> _
Public ReadOnly Property StorageElement As StorageElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As StorageElement

value = instance.StorageElement
```

``` csharp
[ConfigurationPropertyAttribute("storage")]
public StorageElement StorageElement { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"storage")]
public:
property StorageElement^ StorageElement {
    StorageElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.StorageElement](storageelement-class-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

