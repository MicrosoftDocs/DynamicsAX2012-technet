---
title: ICachedChannelDataManager.PutChannelById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelbyid(v=AX.60)
ms:contentKeyID: 62210562
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelById
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the online channel by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelById ( _
    channelId As Long, _
    result As Channel _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim result As Channel

instance.PutChannelById(channelId, result)
```

``` csharp
void PutChannelById(
    long channelId,
    Channel result
)
```

``` c++
void PutChannelById(
    long long channelId, 
    Channel^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

