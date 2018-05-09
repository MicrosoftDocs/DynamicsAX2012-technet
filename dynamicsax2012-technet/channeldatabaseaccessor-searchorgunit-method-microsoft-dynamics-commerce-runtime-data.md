---
title: ChannelDatabaseAccessor.SearchOrgUnit Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SearchOrgUnit Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.SearchOrgUnit(Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.searchorgunit(v=AX.60)
ms:contentKeyID: 65322681
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.SearchOrgUnit
dev_langs:
- CSharp
- C++
- VB
---

# SearchOrgUnit Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function SearchOrgUnit ( _
    storeSearchCriteria As SearchStoreCriteria, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnit)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim storeSearchCriteria As SearchStoreCriteria
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnit)

returnValue = instance.SearchOrgUnit(storeSearchCriteria, _
    settings)
```

``` csharp
public ReadOnlyCollection<OrgUnit> SearchOrgUnit(
    SearchStoreCriteria storeSearchCriteria,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<OrgUnit^>^ SearchOrgUnit(
    SearchStoreCriteria^ storeSearchCriteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - storeSearchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria](searchstorecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

