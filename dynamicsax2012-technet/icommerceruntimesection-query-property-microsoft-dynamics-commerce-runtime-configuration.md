---
title: ICommerceRuntimeSection.Query Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Query Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Query
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.query(v=AX.60)
ms:contentKeyID: 65320163
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Query
dev_langs:
- CSharp
- C++
- VB
---

# Query Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the query element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Query As IQueryElement
    Get
'Usage
Dim instance As ICommerceRuntimeSection
Dim value As IQueryElement

value = instance.Query
```

``` csharp
IQueryElement Query { get; }
```

``` c++
property IQueryElement^ Query {
    IQueryElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement](iqueryelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [IQueryElement](iqueryelement-interface-microsoft-dynamics-commerce-runtime-configuration.md).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

