---
title: InventoryManager.GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit), SearchArea) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit), SearchArea)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStoreAvailabilities(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getstoreavailabilities(v=AX.60)
ms:contentKeyID: 65319431
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit), SearchArea)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreAvailabilities ( _
    settings As QueryResultSettings, _
    items As IEnumerable(Of ItemUnit), _
    searchArea As SearchArea _
) As ReadOnlyCollection(Of OrgUnitAvailability)
'Usage
Dim instance As InventoryManager
Dim settings As QueryResultSettings
Dim items As IEnumerable(Of ItemUnit)
Dim searchArea As SearchArea
Dim returnValue As ReadOnlyCollection(Of OrgUnitAvailability)

returnValue = instance.GetStoreAvailabilities(settings, _
    items, searchArea)
```

``` csharp
public ReadOnlyCollection<OrgUnitAvailability> GetStoreAvailabilities(
    QueryResultSettings settings,
    IEnumerable<ItemUnit> items,
    SearchArea searchArea
)
```

``` c++
public:
ReadOnlyCollection<OrgUnitAvailability^>^ GetStoreAvailabilities(
    QueryResultSettings^ settings, 
    IEnumerable<ItemUnit^>^ items, 
    SearchArea^ searchArea
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetStoreAvailabilities Overload](inventorymanager-getstoreavailabilities-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

