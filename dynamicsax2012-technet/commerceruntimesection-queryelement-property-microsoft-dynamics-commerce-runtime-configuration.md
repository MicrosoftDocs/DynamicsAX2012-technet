---
title: CommerceRuntimeSection.QueryElement Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: QueryElement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.QueryElement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.queryelement(v=AX.60)
ms:contentKeyID: 65322375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.QueryElement
dev_langs:
- CSharp
- C++
- VB
---

# QueryElement Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("query")> _
Public ReadOnly Property QueryElement As QueryElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As QueryElement

value = instance.QueryElement
```

``` csharp
[ConfigurationPropertyAttribute("query")]
public QueryElement QueryElement { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"query")]
public:
property QueryElement^ QueryElement {
    QueryElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.QueryElement](queryelement-class-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

