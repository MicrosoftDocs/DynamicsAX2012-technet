---
title: CommerceRuntimeSection.DataAccessSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DataAccessSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.DataAccessSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.dataaccesssettings(v=AX.60)
ms:contentKeyID: 65322936
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.DataAccessSettings
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessSettings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property DataAccessSettings As IDictionary(Of String, String)
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As IDictionary(Of String, String)

value = instance.DataAccessSettings
```

``` csharp
public IDictionary<string, string> DataAccessSettings { get; }
```

``` c++
public:
virtual property IDictionary<String^, String^>^ DataAccessSettings {
    IDictionary<String^, String^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Implements

[ICommerceRuntimeSection.DataAccessSettings](icommerceruntimesection-dataaccesssettings-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

