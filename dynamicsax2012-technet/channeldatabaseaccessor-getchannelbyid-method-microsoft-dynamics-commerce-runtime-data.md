---
title: ChannelDatabaseAccessor.GetChannelById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelById(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getchannelbyid(v=AX.60)
ms:contentKeyID: 62210296
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelById
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelById Method

Gets the online channel by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelById ( _
    channelId As Long _
) As Channel
'Usage
Dim instance As ChannelDatabaseAccessor
Dim channelId As Long
Dim returnValue As Channel

returnValue = instance.GetChannelById(channelId)
```

``` csharp
public Channel GetChannelById(
    long channelId
)
```

``` c++
public:
virtual Channel^ GetChannelById(
    long long channelId
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel or NULL if not found.  

#### Implements

[IChannelDataManager.GetChannelById(Int64)](ichanneldatamanager-getchannelbyid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

