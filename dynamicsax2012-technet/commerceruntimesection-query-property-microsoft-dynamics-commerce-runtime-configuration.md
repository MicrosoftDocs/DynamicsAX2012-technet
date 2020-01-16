---
title: CommerceRuntimeSection.Query Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Query Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Query
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.query(v=AX.60)
ms:contentKeyID: 49852853
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Query
dev_langs:
- CSharp
- C++
- VB
---

# Query Property

Gets the query element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Query As IQueryElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As IQueryElement

value = instance.Query
```

``` csharp
public IQueryElement Query { get; }
```

``` c++
public:
virtual property IQueryElement^ Query {
    IQueryElement^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement](iqueryelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [QueryElement](queryelement-class-microsoft-dynamics-commerce-runtime-configuration.md).  

#### Implements

[ICommerceRuntimeSection.Query](icommerceruntimesection-query-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

