---
title: PricingDataServiceManager.GetPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPriceGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getpricegroups(v=AX.60)
ms:contentKeyID: 65321938
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetPriceGroups ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of PriceGroup)
'Usage
Dim instance As PricingDataServiceManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of PriceGroup)

returnValue = instance.GetPriceGroups(settings)
```

``` csharp
public ReadOnlyCollection<PriceGroup> GetPriceGroups(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<PriceGroup^>^ GetPriceGroups(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManager.GetPriceGroups(QueryResultSettings)](ipricingdatamanager-getpricegroups-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

