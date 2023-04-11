---
title: IChannelDataManager.GetChannelProfileByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelProfileByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelProfileByChannelId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelprofilebychannelid(v=AX.60)
ms:contentKeyID: 62210520
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelProfileByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProfileByChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelProfileByChannelId ( _
    channelId As Long, _
    columns As ColumnSet _
) As ChannelProfile
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim columns As ColumnSet
Dim returnValue As ChannelProfile

returnValue = instance.GetChannelProfileByChannelId(channelId, _
    columns)
```

``` csharp
ChannelProfile GetChannelProfileByChannelId(
    long channelId,
    ColumnSet columns
)
```

``` c++
ChannelProfile^ GetChannelProfileByChannelId(
    long long channelId, 
    ColumnSet^ columns
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel profile.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

