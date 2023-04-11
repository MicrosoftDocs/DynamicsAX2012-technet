---
title: ChannelDatabaseAccessor.GetCurrencies Method (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrencies Method (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetCurrencies(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getcurrencies(v=AX.60)
ms:contentKeyID: 65319608
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCurrencies Method (String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrencies ( _
    currencyCode As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Currency)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim currencyCode As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Currency)

returnValue = instance.GetCurrencies(currencyCode, _
    settings)
```

``` csharp
public ReadOnlyCollection<Currency> GetCurrencies(
    string currencyCode,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<Currency^>^ GetCurrencies(
    String^ currencyCode, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetCurrencies(String, QueryResultSettings)](ichanneldatamanager-getcurrencies-method-string-queryresultsettings-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetCurrencies Overload](channeldatabaseaccessor-getcurrencies-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

