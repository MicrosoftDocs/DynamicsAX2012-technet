---
title: IChannelDataManager.GetOnlineChannelById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetOnlineChannelById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetOnlineChannelById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getonlinechannelbyid(v=AX.60)
ms:contentKeyID: 62211033
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetOnlineChannelById
dev_langs:
- CSharp
- C++
- VB
---

# GetOnlineChannelById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the online channel by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetOnlineChannelById ( _
    channelId As Long, _
    columns As ColumnSet _
) As OnlineChannel
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim columns As ColumnSet
Dim returnValue As OnlineChannel

returnValue = instance.GetOnlineChannelById(channelId, _
    columns)
```

``` csharp
OnlineChannel GetOnlineChannelById(
    long channelId,
    ColumnSet columns
)
```

``` c++
OnlineChannel^ GetOnlineChannelById(
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

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The online channel.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

