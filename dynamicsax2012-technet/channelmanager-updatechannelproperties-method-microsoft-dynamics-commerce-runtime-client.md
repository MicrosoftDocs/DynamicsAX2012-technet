---
title: ChannelManager.UpdateChannelProperties Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateChannelProperties Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.UpdateChannelProperties(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProperty})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.channelmanager.updatechannelproperties(v=AX.60)
ms:contentKeyID: 49819151
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.UpdateChannelProperties
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelProperties Method

Updates channel properties for the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateChannelProperties ( _
    channelProperties As IEnumerable(Of ChannelProperty) _
)
'Usage
Dim instance As ChannelManager
Dim channelProperties As IEnumerable(Of ChannelProperty)

instance.UpdateChannelProperties(channelProperties)
```

``` csharp
public void UpdateChannelProperties(
    IEnumerable<ChannelProperty> channelProperties
)
```

``` c++
public:
void UpdateChannelProperties(
    IEnumerable<ChannelProperty^>^ channelProperties
)
```

#### Parameters

  - channelProperties  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ChannelProperty](channelproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

