---
title: ICachedChargeDataManager.PutChargeConfigurationsByHeader Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChargeConfigurationsByHeader Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeConfigurationsByHeader(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLevel,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchargedatamanager.putchargeconfigurationsbyheader(v=AX.60)
ms:contentKeyID: 65319579
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeConfigurationsByHeader
dev_langs:
- CSharp
- C++
- VB
---

# PutChargeConfigurationsByHeader Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the charge configuration by header.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChargeConfigurationsByHeader ( _
    settings As QueryResultSettings, _
    chargeType As ChargeLevel, _
    header As ChargeConfigurationHeader, _
    result As ReadOnlyCollection(Of ChargeConfiguration) _
)
'Usage
Dim instance As ICachedChargeDataManager
Dim settings As QueryResultSettings
Dim chargeType As ChargeLevel
Dim header As ChargeConfigurationHeader
Dim result As ReadOnlyCollection(Of ChargeConfiguration)

instance.PutChargeConfigurationsByHeader(settings, _
    chargeType, header, result)
```

``` csharp
void PutChargeConfigurationsByHeader(
    QueryResultSettings settings,
    ChargeLevel chargeType,
    ChargeConfigurationHeader header,
    ReadOnlyCollection<ChargeConfiguration> result
)
```

``` c++
void PutChargeConfigurationsByHeader(
    QueryResultSettings^ settings, 
    ChargeLevel chargeType, 
    ChargeConfigurationHeader^ header, 
    ReadOnlyCollection<ChargeConfiguration^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - chargeType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLevel](chargelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - header  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChargeConfiguration](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChargeDataManager Interface](icachedchargedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

