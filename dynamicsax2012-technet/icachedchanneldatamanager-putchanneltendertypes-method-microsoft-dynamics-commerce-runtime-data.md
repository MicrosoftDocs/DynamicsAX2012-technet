---
title: ICachedChannelDataManager.PutChannelTenderTypes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelTenderTypes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelTenderTypes(System.Int64,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchanneltendertypes(v=AX.60)
ms:contentKeyID: 65321029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelTenderTypes
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelTenderTypes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelTenderTypes ( _
    channelId As Long, _
    countingRequired As Nullable(Of Integer), _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of TenderType) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim countingRequired As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of TenderType)

instance.PutChannelTenderTypes(channelId, _
    countingRequired, settings, result)
```

``` csharp
void PutChannelTenderTypes(
    long channelId,
    Nullable<int> countingRequired,
    QueryResultSettings settings,
    ReadOnlyCollection<TenderType> result
)
```

``` c++
void PutChannelTenderTypes(
    long long channelId, 
    Nullable<int> countingRequired, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<TenderType^>^ result
)
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

