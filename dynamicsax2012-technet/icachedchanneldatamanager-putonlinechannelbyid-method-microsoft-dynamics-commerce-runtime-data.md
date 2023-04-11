---
title: ICachedChannelDataManager.PutOnlineChannelById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutOnlineChannelById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutOnlineChannelById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putonlinechannelbyid(v=AX.60)
ms:contentKeyID: 62201836
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutOnlineChannelById
dev_langs:
- CSharp
- C++
- VB
---

# PutOnlineChannelById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the online channel by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutOnlineChannelById ( _
    channelId As Long, _
    columns As ColumnSet, _
    result As OnlineChannel _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim columns As ColumnSet
Dim result As OnlineChannel

instance.PutOnlineChannelById(channelId, _
    columns, result)
```

``` csharp
void PutOnlineChannelById(
    long channelId,
    ColumnSet columns,
    OnlineChannel result
)
```

``` c++
void PutOnlineChannelById(
    long long channelId, 
    ColumnSet^ columns, 
    OnlineChannel^ result
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
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

