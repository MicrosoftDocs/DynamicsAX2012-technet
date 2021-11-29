---
title: ChannelCategoryAttribute.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.ChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.channelid(v=AX.60)
ms:contentKeyID: 65319261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("HOSTCHANNEL")> _
Public Property ChannelId As Long
    Get
    Friend Set
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As Long

value = instance.ChannelId
```

``` csharp
[ColumnAttribute("HOSTCHANNEL")]
public long ChannelId { get; internal set; }
```

``` c++
[ColumnAttribute(L"HOSTCHANNEL")]
public:
property long long ChannelId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

