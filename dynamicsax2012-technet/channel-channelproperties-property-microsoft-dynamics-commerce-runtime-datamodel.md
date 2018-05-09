---
title: Channel.ChannelProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channel.channelproperties(v=AX.60)
ms:contentKeyID: 49856749
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelProperties
dev_langs:
- CSharp
- C++
- VB
---

# ChannelProperties Property

Gets the channel properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelProperties As ReadOnlyCollection(Of ChannelProperty)
    Get
    Set
'Usage
Dim instance As Channel
Dim value As ReadOnlyCollection(Of ChannelProperty)

value = instance.ChannelProperties

instance.ChannelProperties = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ChannelProperty> ChannelProperties { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ChannelProperty^>^ ChannelProperties {
    ReadOnlyCollection<ChannelProperty^>^ get ();
    void set (ReadOnlyCollection<ChannelProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ChannelProperty](channelproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The channel properties.  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

