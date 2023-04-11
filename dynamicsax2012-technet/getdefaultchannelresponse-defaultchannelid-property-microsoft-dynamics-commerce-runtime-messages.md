---
title: GetDefaultChannelResponse.DefaultChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DefaultChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDefaultChannelResponse.DefaultChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdefaultchannelresponse.defaultchannelid(v=AX.60)
ms:contentKeyID: 62208426
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDefaultChannelResponse.DefaultChannelId
dev_langs:
- CSharp
- C++
- VB
---

# DefaultChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DefaultChannelId As Long
    Get
    Private Set
'Usage
Dim instance As GetDefaultChannelResponse
Dim value As Long

value = instance.DefaultChannelId
```

``` csharp
[DataMemberAttribute]
public long DefaultChannelId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long DefaultChannelId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetDefaultChannelResponse Class](getdefaultchannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

