---
title: ChannelDatabaseAccessor.GetStores Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStores(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getstores(v=AX.60)
ms:contentKeyID: 65319795
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStores
dev_langs:
- CSharp
- C++
- VB
---

# GetStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStores ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnit)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnit)

returnValue = instance.GetStores(settings)
```

``` csharp
public ReadOnlyCollection<OrgUnit> GetStores(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<OrgUnit^>^ GetStores(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetStores(QueryResultSettings)](ichanneldatamanager-getstores-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

