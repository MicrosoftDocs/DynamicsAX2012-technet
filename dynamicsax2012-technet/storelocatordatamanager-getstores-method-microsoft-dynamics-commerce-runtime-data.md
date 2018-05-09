---
title: StoreLocatorDataManager.GetStores Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StoreLocatorDataManager.GetStores(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.storelocatordatamanager.getstores(v=AX.60)
ms:contentKeyID: 65319576
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StoreLocatorDataManager.GetStores
dev_langs:
- CSharp
- C++
- VB
---

# GetStores Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStores ( _
    channelId As Long, _
    searchArea As SearchArea, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnitLocation)
'Usage
Dim instance As StoreLocatorDataManager
Dim channelId As Long
Dim searchArea As SearchArea
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnitLocation)

returnValue = instance.GetStores(channelId, _
    searchArea, settings)
```

``` csharp
public ReadOnlyCollection<OrgUnitLocation> GetStores(
    long channelId,
    SearchArea searchArea,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<OrgUnitLocation^>^ GetStores(
    long long channelId, 
    SearchArea^ searchArea, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreLocatorDataManager Class](storelocatordatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

