---
title: GetChannelCategoryAttributesDataRequest.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.ChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getchannelcategoryattributesdatarequest.channelid(v=AX.60)
ms:contentKeyID: 65320338
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ChannelId As Long
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryAttributesDataRequest
Dim value As Long

value = instance.ChannelId
```

``` csharp
public long ChannelId { get; private set; }
```

``` c++
public:
property long long ChannelId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryAttributesDataRequest Class](getchannelcategoryattributesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

