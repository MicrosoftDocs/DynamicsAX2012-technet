---
title: Channel.ChannelProfile Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channel.channelprofile(v=AX.60)
ms:contentKeyID: 49855945
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelProfile
dev_langs:
- CSharp
- C++
- VB
---

# ChannelProfile Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the channel profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelProfile As ChannelProfile
    Get
    Set
'Usage
Dim instance As Channel
Dim value As ChannelProfile

value = instance.ChannelProfile

instance.ChannelProfile = value
```

``` csharp
[DataMemberAttribute]
public ChannelProfile ChannelProfile { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ChannelProfile^ ChannelProfile {
    ChannelProfile^ get ();
    void set (ChannelProfile^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

