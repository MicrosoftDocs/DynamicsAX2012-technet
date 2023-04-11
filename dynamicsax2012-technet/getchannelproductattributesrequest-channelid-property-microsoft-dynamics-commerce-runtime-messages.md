---
title: GetChannelProductAttributesRequest.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesRequest.ChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelproductattributesrequest.channelid(v=AX.60)
ms:contentKeyID: 49843053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesRequest.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelId As Long
    Get
    Set
'Usage
Dim instance As GetChannelProductAttributesRequest
Dim value As Long

value = instance.ChannelId

instance.ChannelId = value
```

``` csharp
[DataMemberAttribute]
public long ChannelId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ChannelId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The channel identifier.  

## See Also

#### Reference

[GetChannelProductAttributesRequest Class](getchannelproductattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

