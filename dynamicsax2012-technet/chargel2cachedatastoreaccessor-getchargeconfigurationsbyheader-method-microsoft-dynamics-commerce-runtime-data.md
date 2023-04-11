---
title: ChargeL2CacheDataStoreAccessor.GetChargeConfigurationsByHeader Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChargeConfigurationsByHeader Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetChargeConfigurationsByHeader(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLevel,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargel2cachedatastoreaccessor.getchargeconfigurationsbyheader(v=AX.60)
ms:contentKeyID: 65319060
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetChargeConfigurationsByHeader
dev_langs:
- CSharp
- C++
- VB
---

# GetChargeConfigurationsByHeader Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This method retrieves all auto-charge configurations of the given type (header/line) that match the given header information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChargeConfigurationsByHeader ( _
    settings As QueryResultSettings, _
    chargeType As ChargeLevel, _
    header As ChargeConfigurationHeader _
) As ReadOnlyCollection(Of ChargeConfiguration)
'Usage
Dim instance As ChargeL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim chargeType As ChargeLevel
Dim header As ChargeConfigurationHeader
Dim returnValue As ReadOnlyCollection(Of ChargeConfiguration)

returnValue = instance.GetChargeConfigurationsByHeader(settings, _
    chargeType, header)
```

``` csharp
public ReadOnlyCollection<ChargeConfiguration> GetChargeConfigurationsByHeader(
    QueryResultSettings settings,
    ChargeLevel chargeType,
    ChargeConfigurationHeader header
)
```

``` c++
public:
virtual ReadOnlyCollection<ChargeConfiguration^>^ GetChargeConfigurationsByHeader(
    QueryResultSettings^ settings, 
    ChargeLevel chargeType, 
    ChargeConfigurationHeader^ header
) sealed
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChargeConfiguration](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of auto-charge configurations that match the given header and charge type.  

#### Implements

[ICachedChargeDataManager.GetChargeConfigurationsByHeader(QueryResultSettings, ChargeLevel, ChargeConfigurationHeader)](icachedchargedatamanager-getchargeconfigurationsbyheader-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeL2CacheDataStoreAccessor Class](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

