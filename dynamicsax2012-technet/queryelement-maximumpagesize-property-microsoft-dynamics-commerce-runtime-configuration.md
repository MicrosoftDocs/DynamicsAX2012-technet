---
title: QueryElement.MaximumPageSize Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: MaximumPageSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.QueryElement.MaximumPageSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.queryelement.maximumpagesize(v=AX.60)
ms:contentKeyID: 49843028
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.QueryElement.MaximumPageSize
dev_langs:
- CSharp
- C++
- VB
---

# MaximumPageSize Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum page size for the PagingInfo class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("maxPageSize", DefaultValue := )> _
Public ReadOnly Property MaximumPageSize As Integer
    Get
'Usage
Dim instance As QueryElement
Dim value As Integer

value = instance.MaximumPageSize
```

``` csharp
[ConfigurationPropertyAttribute("maxPageSize", DefaultValue = )]
public int MaximumPageSize { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"maxPageSize", DefaultValue = )]
public:
virtual property int MaximumPageSize {
    int get () sealed;
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

#### Implements

[IQueryElement.MaximumPageSize](iqueryelement-maximumpagesize-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## Remarks

The largest value used regardless of what page size has been requested.

## See Also

#### Reference

[QueryElement Class](queryelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

