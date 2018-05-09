---
title: InventoryManager.GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStoreAvailabilities(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getstoreavailabilities(v=AX.60)
ms:contentKeyID: 65322008
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreAvailabilities Method (QueryResultSettings, IEnumerable(ItemUnit))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreAvailabilities ( _
    settings As QueryResultSettings, _
    items As IEnumerable(Of ItemUnit) _
) As ReadOnlyCollection(Of OrgUnitAvailability)
'Usage
Dim instance As InventoryManager
Dim settings As QueryResultSettings
Dim items As IEnumerable(Of ItemUnit)
Dim returnValue As ReadOnlyCollection(Of OrgUnitAvailability)

returnValue = instance.GetStoreAvailabilities(settings, _
    items)
```

``` csharp
public ReadOnlyCollection<OrgUnitAvailability> GetStoreAvailabilities(
    QueryResultSettings settings,
    IEnumerable<ItemUnit> items
)
```

``` c++
public:
ReadOnlyCollection<OrgUnitAvailability^>^ GetStoreAvailabilities(
    QueryResultSettings^ settings, 
    IEnumerable<ItemUnit^>^ items
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetStoreAvailabilities Overload](inventorymanager-getstoreavailabilities-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

