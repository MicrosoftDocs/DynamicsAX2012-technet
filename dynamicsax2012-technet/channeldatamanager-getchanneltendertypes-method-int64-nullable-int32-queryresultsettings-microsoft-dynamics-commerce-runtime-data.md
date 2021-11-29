---
title: ChannelDataManager.GetChannelTenderTypes Method (Int64, Nullable(Int32), QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelTenderTypes Method (Int64, Nullable(Int32), QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetChannelTenderTypes(System.Int64,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getchanneltendertypes(v=AX.60)
ms:contentKeyID: 65320382
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelTenderTypes Method (Int64, Nullable(Int32), QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelTenderTypes ( _
    channelId As Long, _
    countingRequired As Nullable(Of Integer), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TenderType)
'Usage
Dim instance As ChannelDataManager
Dim channelId As Long
Dim countingRequired As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TenderType)

returnValue = instance.GetChannelTenderTypes(channelId, _
    countingRequired, settings)
```

``` csharp
public ReadOnlyCollection<TenderType> GetChannelTenderTypes(
    long channelId,
    Nullable<int> countingRequired,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<TenderType^>^ GetChannelTenderTypes(
    long long channelId, 
    Nullable<int> countingRequired, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - countingRequired  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetChannelTenderTypes(Int64, Nullable\<Int32\>, QueryResultSettings)](ichanneldatamanager-getchanneltendertypes-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetChannelTenderTypes Overload](channeldatamanager-getchanneltendertypes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

