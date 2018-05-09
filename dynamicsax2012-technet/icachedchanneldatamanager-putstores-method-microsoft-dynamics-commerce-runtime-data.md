---
title: ICachedChannelDataManager.PutStores Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutStores(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putstores(v=AX.60)
ms:contentKeyID: 65322640
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutStores
dev_langs:
- CSharp
- C++
- VB
---

# PutStores Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutStores ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of OrgUnit) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of OrgUnit)

instance.PutStores(settings, result)
```

``` csharp
void PutStores(
    QueryResultSettings settings,
    ReadOnlyCollection<OrgUnit> result
)
```

``` c++
void PutStores(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<OrgUnit^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

