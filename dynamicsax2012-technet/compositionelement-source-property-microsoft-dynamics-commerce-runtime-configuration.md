---
title: CompositionElement.Source Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionElement.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.compositionelement.source(v=AX.60)
ms:contentKeyID: 49837987
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionElement.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property

Gets the load source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("source", IsRequired := True)> _
Public ReadOnly Property Source As String
    Get
'Usage
Dim instance As CompositionElement
Dim value As String

value = instance.Source
```

``` csharp
[ConfigurationPropertyAttribute("source", IsRequired = true)]
public string Source { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"source", IsRequired = true)]
public:
virtual property String^ Source {
    String^ get () sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

#### Implements

[ICompositionElement.Source](icompositionelement-source-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## Remarks

Supported values include type, assembly or directory.

## See Also

#### Reference

[CompositionElement Class](compositionelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

