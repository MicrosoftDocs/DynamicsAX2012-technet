---
title: CompositionElement.Value Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionElement.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.compositionelement.value(v=AX.60)
ms:contentKeyID: 49856582
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionElement.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value for the load source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("value", IsRequired := True)> _
Public ReadOnly Property Value As String
    Get
'Usage
Dim instance As CompositionElement
Dim value As String

value = instance.Value
```

``` csharp
[ConfigurationPropertyAttribute("value", IsRequired = true)]
public string Value { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"value", IsRequired = true)]
public:
virtual property String^ Value {
    String^ get () sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

#### Implements

[ICompositionElement.Value](icompositionelement-value-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CompositionElement Class](compositionelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

