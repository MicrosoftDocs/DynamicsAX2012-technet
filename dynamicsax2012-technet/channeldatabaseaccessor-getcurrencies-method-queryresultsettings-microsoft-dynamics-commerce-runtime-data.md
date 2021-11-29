---
title: ChannelDatabaseAccessor.GetCurrencies Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrencies Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getcurrencies(v=AX.60)
ms:contentKeyID: 65322868
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCurrencies Method (QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrencies ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Currency)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Currency)

returnValue = instance.GetCurrencies(settings)
```

``` csharp
public ReadOnlyCollection<Currency> GetCurrencies(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<Currency^>^ GetCurrencies(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetCurrencies(QueryResultSettings)](ichanneldatamanager-getcurrencies-method-queryresultsettings-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetCurrencies Overload](channeldatabaseaccessor-getcurrencies-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

