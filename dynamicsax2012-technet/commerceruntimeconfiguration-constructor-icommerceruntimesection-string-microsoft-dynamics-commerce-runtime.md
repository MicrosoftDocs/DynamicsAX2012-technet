---
title: CommerceRuntimeConfiguration Constructor (ICommerceRuntimeSection, String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CommerceRuntimeConfiguration Constructor (ICommerceRuntimeSection, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.#ctor(Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.commerceruntimeconfiguration(v=AX.60)
ms:contentKeyID: 65320199
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeConfiguration Constructor (ICommerceRuntimeSection, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commerceRuntimeSection As ICommerceRuntimeSection, _
    connectionString As String _
)
'Usage
Dim commerceRuntimeSection As ICommerceRuntimeSection
Dim connectionString As String

Dim instance As New CommerceRuntimeConfiguration(commerceRuntimeSection, _
    connectionString)
```

``` csharp
public CommerceRuntimeConfiguration(
    ICommerceRuntimeSection commerceRuntimeSection,
    string connectionString
)
```

``` c++
public:
CommerceRuntimeConfiguration(
    ICommerceRuntimeSection^ commerceRuntimeSection, 
    String^ connectionString
)
```

#### Parameters

  - commerceRuntimeSection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)  

<!-- end list -->

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[CommerceRuntimeConfiguration Overload](commerceruntimeconfiguration-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

