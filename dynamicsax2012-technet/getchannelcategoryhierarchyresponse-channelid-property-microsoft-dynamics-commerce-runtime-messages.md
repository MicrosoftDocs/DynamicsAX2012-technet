---
title: GetChannelCategoryHierarchyResponse.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.ChannelId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryhierarchyresponse.channelid(v=AX.60)
ms:contentKeyID: 49856763
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property

Gets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelId As Long
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryHierarchyResponse
Dim value As Long

value = instance.ChannelId
```

``` csharp
[DataMemberAttribute]
public long ChannelId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ChannelId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryHierarchyResponse Class](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

