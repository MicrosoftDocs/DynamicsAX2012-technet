---
title: CommerceRuntimeSection.DataAccessElement Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DataAccessElement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.DataAccessElement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.dataaccesselement(v=AX.60)
ms:contentKeyID: 65323156
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.DataAccessElement
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessElement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("dataAccess", IsDefaultCollection := True)> _
Public ReadOnly Property DataAccessElement As NameValueConfigurationCollection
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As NameValueConfigurationCollection

value = instance.DataAccessElement
```

``` csharp
[ConfigurationPropertyAttribute("dataAccess", IsDefaultCollection = true)]
public NameValueConfigurationCollection DataAccessElement { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"dataAccess", IsDefaultCollection = true)]
public:
property NameValueConfigurationCollection^ DataAccessElement {
    NameValueConfigurationCollection^ get ();
}
```

#### Property Value

Type: [System.Configuration.NameValueConfigurationCollection](https://technet.microsoft.com/library/ms134603\(v=ax.60\))  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

