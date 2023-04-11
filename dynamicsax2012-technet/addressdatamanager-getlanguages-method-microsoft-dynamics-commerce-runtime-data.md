---
title: AddressDataManager.GetLanguages Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLanguages Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.AddressDataManager.GetLanguages(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.addressdatamanager.getlanguages(v=AX.60)
ms:contentKeyID: 65319899
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.AddressDataManager.GetLanguages
dev_langs:
- CSharp
- C++
- VB
---

# GetLanguages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLanguages ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of SupportedLanguage)
'Usage
Dim instance As AddressDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of SupportedLanguage)

returnValue = instance.GetLanguages(settings)
```

``` csharp
public ReadOnlyCollection<SupportedLanguage> GetLanguages(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<SupportedLanguage^>^ GetLanguages(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SupportedLanguage](supportedlanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[AddressDataManager Class](addressdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

