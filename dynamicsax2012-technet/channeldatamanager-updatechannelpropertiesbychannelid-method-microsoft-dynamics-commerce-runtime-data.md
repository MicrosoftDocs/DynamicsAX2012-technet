---
title: ChannelDataManager.UpdateChannelPropertiesByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UpdateChannelPropertiesByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.UpdateChannelPropertiesByChannelId(System.Int64,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProperty})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.updatechannelpropertiesbychannelid(v=AX.60)
ms:contentKeyID: 62210350
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.UpdateChannelPropertiesByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelPropertiesByChannelId Method

Sets the channel-specific properties of the specified channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateChannelPropertiesByChannelId ( _
    channelId As Long, _
    channelProperties As ReadOnlyCollection(Of ChannelProperty) _
)
'Usage
Dim instance As ChannelDataManager
Dim channelId As Long
Dim channelProperties As ReadOnlyCollection(Of ChannelProperty)

instance.UpdateChannelPropertiesByChannelId(channelId, _
    channelProperties)
```

``` csharp
public void UpdateChannelPropertiesByChannelId(
    long channelId,
    ReadOnlyCollection<ChannelProperty> channelProperties
)
```

``` c++
public:
void UpdateChannelPropertiesByChannelId(
    long long channelId, 
    ReadOnlyCollection<ChannelProperty^>^ channelProperties
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - channelProperties  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ChannelProperty](channelproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

