---
title: StoreLocatorManager.GetStoreLocations Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStoreLocations Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreLocatorManager.GetStoreLocations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.storelocatormanager.getstorelocations(v=AX.60)
ms:contentKeyID: 65319514
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreLocations Method (QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreLocations ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnitLocation)
'Usage
Dim instance As StoreLocatorManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnitLocation)

returnValue = instance.GetStoreLocations(settings)
```

``` csharp
public ReadOnlyCollection<OrgUnitLocation> GetStoreLocations(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<OrgUnitLocation^>^ GetStoreLocations(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreLocatorManager Class](storelocatormanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetStoreLocations Overload](storelocatormanager-getstorelocations-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

