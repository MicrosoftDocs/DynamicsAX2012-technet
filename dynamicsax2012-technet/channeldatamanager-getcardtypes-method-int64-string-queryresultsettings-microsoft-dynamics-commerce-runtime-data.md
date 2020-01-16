---
title: ChannelDataManager.GetCardTypes Method (Int64, String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCardTypes Method (Int64, String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetCardTypes(System.Int64,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getcardtypes(v=AX.60)
ms:contentKeyID: 65316950
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypes Method (Int64, String, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCardTypes ( _
    channelId As Long, _
    id As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CardTypeInfo)
'Usage
Dim instance As ChannelDataManager
Dim channelId As Long
Dim id As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of CardTypeInfo)

returnValue = instance.GetCardTypes(channelId, _
    id, settings)
```

``` csharp
public ReadOnlyCollection<CardTypeInfo> GetCardTypes(
    long channelId,
    string id,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<CardTypeInfo^>^ GetCardTypes(
    long long channelId, 
    String^ id, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetCardTypes(Int64, String, QueryResultSettings)](ichanneldatamanager-getcardtypes-method-int64-string-queryresultsettings-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetCardTypes Overload](channeldatamanager-getcardtypes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

