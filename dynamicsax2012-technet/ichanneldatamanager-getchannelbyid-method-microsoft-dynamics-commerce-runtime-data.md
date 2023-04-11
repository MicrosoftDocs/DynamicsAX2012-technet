---
title: IChannelDataManager.GetChannelById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelById(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelbyid(v=AX.60)
ms:contentKeyID: 62208363
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelById
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the online channel by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelById ( _
    channelId As Long _
) As Channel
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim returnValue As Channel

returnValue = instance.GetChannelById(channelId)
```

``` csharp
Channel GetChannelById(
    long channelId
)
```

``` c++
Channel^ GetChannelById(
    long long channelId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel or NULL if not found.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

