---
title: ICachedChannelDataManager.PutChannelProfileByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelProfileByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelProfileByChannelId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelprofilebychannelid(v=AX.60)
ms:contentKeyID: 62202334
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelProfileByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelProfileByChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the channel profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelProfileByChannelId ( _
    channelId As Long, _
    columns As ColumnSet, _
    result As ChannelProfile _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim columns As ColumnSet
Dim result As ChannelProfile

instance.PutChannelProfileByChannelId(channelId, _
    columns, result)
```

``` csharp
void PutChannelProfileByChannelId(
    long channelId,
    ColumnSet columns,
    ChannelProfile result
)
```

``` c++
void PutChannelProfileByChannelId(
    long long channelId, 
    ColumnSet^ columns, 
    ChannelProfile^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

