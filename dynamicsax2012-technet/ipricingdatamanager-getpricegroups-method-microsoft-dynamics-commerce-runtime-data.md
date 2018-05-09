---
title: IPricingDataManager.GetPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPriceGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getpricegroups(v=AX.60)
ms:contentKeyID: 65319849
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetPriceGroups ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of PriceGroup)
'Usage
Dim instance As IPricingDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of PriceGroup)

returnValue = instance.GetPriceGroups(settings)
```

``` csharp
ReadOnlyCollection<PriceGroup> GetPriceGroups(
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<PriceGroup^>^ GetPriceGroups(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

