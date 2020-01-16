---
title: ItemAvailabilityDataManager.GetItemAvailabilitiesByItemWarehouses Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemAvailabilitiesByItemWarehouses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItemWarehouses(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemavailabilitydatamanager.getitemavailabilitiesbyitemwarehouses(v=AX.60)
ms:contentKeyID: 65319238
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItemWarehouses
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemWarehouses Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemAvailabilitiesByItemWarehouses ( _
    itemWarehouses As IEnumerable(Of ItemWarehouse), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ItemAvailability)
'Usage
Dim instance As ItemAvailabilityDataManager
Dim itemWarehouses As IEnumerable(Of ItemWarehouse)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ItemAvailability)

returnValue = instance.GetItemAvailabilitiesByItemWarehouses(itemWarehouses, _
    settings)
```

``` csharp
public ReadOnlyCollection<ItemAvailability> GetItemAvailabilitiesByItemWarehouses(
    IEnumerable<ItemWarehouse> itemWarehouses,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ItemAvailability^>^ GetItemAvailabilitiesByItemWarehouses(
    IEnumerable<ItemWarehouse^>^ itemWarehouses, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemWarehouses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemAvailabilityDataManager Class](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

