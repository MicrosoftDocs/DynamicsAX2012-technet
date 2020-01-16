---
title: QueryElement.DefaultPageSize Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DefaultPageSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.QueryElement.DefaultPageSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.queryelement.defaultpagesize(v=AX.60)
ms:contentKeyID: 49823482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.QueryElement.DefaultPageSize
dev_langs:
- CSharp
- C++
- VB
---

# DefaultPageSize Property

Gets the default page size for the PagingInfo class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("defaultPageSize", DefaultValue := )> _
Public ReadOnly Property DefaultPageSize As Integer
    Get
'Usage
Dim instance As QueryElement
Dim value As Integer

value = instance.DefaultPageSize
```

``` csharp
[ConfigurationPropertyAttribute("defaultPageSize", DefaultValue = )]
public int DefaultPageSize { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"defaultPageSize", DefaultValue = )]
public:
virtual property int DefaultPageSize {
    int get () sealed;
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

#### Implements

[IQueryElement.DefaultPageSize](iqueryelement-defaultpagesize-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## Remarks

The value used when no page size has been explicitly specified for the query.

## See Also

#### Reference

[QueryElement Class](queryelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

