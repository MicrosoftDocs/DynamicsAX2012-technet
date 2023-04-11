---
title: GetCurrentChannelResponse.CurrentChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CurrentChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrentChannelResponse.CurrentChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcurrentchannelresponse.currentchannelid(v=AX.60)
ms:contentKeyID: 49851689
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrentChannelResponse.CurrentChannelId
dev_langs:
- CSharp
- C++
- VB
---

# CurrentChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the current channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrentChannelId As Long
    Get
    Private Set
'Usage
Dim instance As GetCurrentChannelResponse
Dim value As Long

value = instance.CurrentChannelId
```

``` csharp
[DataMemberAttribute]
public long CurrentChannelId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long CurrentChannelId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetCurrentChannelResponse Class](getcurrentchannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

