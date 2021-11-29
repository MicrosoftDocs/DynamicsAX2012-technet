---
title: CommerceRuntimeConfigurationManager.GetConfigurationSection Method (String) (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: GetConfigurationSection Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeConfigurationManager.GetConfigurationSection(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimeconfigurationmanager.getconfigurationsection(v=AX.60)
ms:contentKeyID: 65320045
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetConfigurationSection Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the configuration section.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetConfigurationSection ( _
    sectionName As String _
) As CommerceRuntimeSection
'Usage
Dim sectionName As String
Dim returnValue As CommerceRuntimeSection

returnValue = CommerceRuntimeConfigurationManager.GetConfigurationSection(sectionName)
```

``` csharp
public static CommerceRuntimeSection GetConfigurationSection(
    string sectionName
)
```

``` c++
public:
static CommerceRuntimeSection^ GetConfigurationSection(
    String^ sectionName
)
```

#### Parameters

  - sectionName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)  
The configuration section.  

## See Also

#### Reference

[CommerceRuntimeConfigurationManager Class](commerceruntimeconfigurationmanager-class-microsoft-dynamics-commerce-runtime-configuration.md)

[GetConfigurationSection Overload](commerceruntimeconfigurationmanager-getconfigurationsection-method-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

