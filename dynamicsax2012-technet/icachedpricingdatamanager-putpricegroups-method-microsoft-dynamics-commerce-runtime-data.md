---
title: ICachedPricingDataManager.PutPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putpricegroups(v=AX.60)
ms:contentKeyID: 65315829
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# PutPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPriceGroups ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of PriceGroup) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of PriceGroup)

instance.PutPriceGroups(settings, result)
```

``` csharp
void PutPriceGroups(
    QueryResultSettings settings,
    ReadOnlyCollection<PriceGroup> result
)
```

``` c++
void PutPriceGroups(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<PriceGroup^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

