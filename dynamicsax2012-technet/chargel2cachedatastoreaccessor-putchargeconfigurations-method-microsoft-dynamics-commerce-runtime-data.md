---
title: ChargeL2CacheDataStoreAccessor.PutChargeConfigurations Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChargeConfigurations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.PutChargeConfigurations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargel2cachedatastoreaccessor.putchargeconfigurations(v=AX.60)
ms:contentKeyID: 65322309
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.PutChargeConfigurations
dev_langs:
- CSharp
- C++
- VB
---

# PutChargeConfigurations Method

Caches the charge configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutChargeConfigurations ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ChargeConfiguration) _
)
'Usage
Dim instance As ChargeL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ChargeConfiguration)

instance.PutChargeConfigurations(settings, _
    result)
```

``` csharp
public void PutChargeConfigurations(
    QueryResultSettings settings,
    ReadOnlyCollection<ChargeConfiguration> result
)
```

``` c++
public:
virtual void PutChargeConfigurations(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<ChargeConfiguration^>^ result
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChargeConfiguration](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[ICachedChargeDataManager.PutChargeConfigurations(QueryResultSettings, ReadOnlyCollection\<ChargeConfiguration\>)](icachedchargedatamanager-putchargeconfigurations-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeL2CacheDataStoreAccessor Class](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

