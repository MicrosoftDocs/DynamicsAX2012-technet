---
title: IChannelDataManager.GetCardTypes Method (Int64, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCardTypes Method (Int64, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetCardTypes(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getcardtypes(v=AX.60)
ms:contentKeyID: 65319703
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypes Method (Int64, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetCardTypes ( _
    channelId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CardTypeInfo)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of CardTypeInfo)

returnValue = instance.GetCardTypes(channelId, _
    settings)
```

``` csharp
ReadOnlyCollection<CardTypeInfo> GetCardTypes(
    long channelId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<CardTypeInfo^>^ GetCardTypes(
    long long channelId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetCardTypes Overload](ichanneldatamanager-getcardtypes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

