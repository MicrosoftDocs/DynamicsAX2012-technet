---
title: ICachedChargeDataManager.PutChargeConfigurations Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChargeConfigurations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeConfigurations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchargedatamanager.putchargeconfigurations(v=AX.60)
ms:contentKeyID: 65321036
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeConfigurations
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
Sub PutChargeConfigurations ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ChargeConfiguration) _
)
'Usage
Dim instance As ICachedChargeDataManager
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ChargeConfiguration)

instance.PutChargeConfigurations(settings, _
    result)
```

``` csharp
void PutChargeConfigurations(
    QueryResultSettings settings,
    ReadOnlyCollection<ChargeConfiguration> result
)
```

``` c++
void PutChargeConfigurations(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<ChargeConfiguration^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChargeConfiguration](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChargeDataManager Interface](icachedchargedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

