---
title: CommerceRuntimeConfigurationManager.GetConfigurationSection Method (Configuration, String) (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: GetConfigurationSection Method (Configuration, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeConfigurationManager.GetConfigurationSection(System.Configuration.Configuration,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimeconfigurationmanager.getconfigurationsection(v=AX.60)
ms:contentKeyID: 65317177
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetConfigurationSection Method (Configuration, String)

Gets the configuration section.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetConfigurationSection ( _
    appConfiguration As Configuration, _
    sectionName As String _
) As CommerceRuntimeSection
'Usage
Dim appConfiguration As Configuration
Dim sectionName As String
Dim returnValue As CommerceRuntimeSection

returnValue = CommerceRuntimeConfigurationManager.GetConfigurationSection(appConfiguration, _
    sectionName)
```

``` csharp
public static CommerceRuntimeSection GetConfigurationSection(
    Configuration appConfiguration,
    string sectionName
)
```

``` c++
public:
static CommerceRuntimeSection^ GetConfigurationSection(
    Configuration^ appConfiguration, 
    String^ sectionName
)
```

#### Parameters

  - appConfiguration  
    Type: [System.Configuration.Configuration](https://technet.microsoft.com/en-us/library/s7kc101z\(v=ax.60\))  

<!-- end list -->

  - sectionName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)  
The configuration section.  

## See Also

#### Reference

[CommerceRuntimeConfigurationManager Class](commerceruntimeconfigurationmanager-class-microsoft-dynamics-commerce-runtime-configuration.md)

[GetConfigurationSection Overload](commerceruntimeconfigurationmanager-getconfigurationsection-method-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

