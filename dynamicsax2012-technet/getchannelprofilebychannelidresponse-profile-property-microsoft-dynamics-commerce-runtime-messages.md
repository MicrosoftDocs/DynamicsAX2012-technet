---
title: GetChannelProfileByChannelIdResponse.Profile Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Profile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdResponse.Profile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelprofilebychannelidresponse.profile(v=AX.60)
ms:contentKeyID: 62213268
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdResponse.Profile
dev_langs:
- CSharp
- C++
- VB
---

# Profile Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Profile As ChannelProfile
    Get
    Private Set
'Usage
Dim instance As GetChannelProfileByChannelIdResponse
Dim value As ChannelProfile

value = instance.Profile
```

``` csharp
[DataMemberAttribute]
public ChannelProfile Profile { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ChannelProfile^ Profile {
    ChannelProfile^ get ();
    private: void set (ChannelProfile^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetChannelProfileByChannelIdResponse Class](getchannelprofilebychannelidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

