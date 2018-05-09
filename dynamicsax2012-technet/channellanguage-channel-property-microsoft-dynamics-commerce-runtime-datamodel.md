---
title: ChannelLanguage.Channel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Channel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.Channel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channellanguage.channel(v=AX.60)
ms:contentKeyID: 49826783
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.Channel
dev_langs:
- CSharp
- C++
- VB
---

# Channel Property

Gets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHANNEL")> _
<DataMemberAttribute> _
Public Property Channel As Long
    Get
    Friend Set
'Usage
Dim instance As ChannelLanguage
Dim value As Long

value = instance.Channel
```

``` csharp
[ColumnAttribute("CHANNEL")]
[DataMemberAttribute]
public long Channel { get; internal set; }
```

``` c++
[ColumnAttribute(L"CHANNEL")]
[DataMemberAttribute]
public:
property long long Channel {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChannelLanguage Class](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

