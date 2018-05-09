---
title: Channel.ChannelLanguages Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelLanguages Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelLanguages
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channel.channellanguages(v=AX.60)
ms:contentKeyID: 49841964
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.ChannelLanguages
dev_langs:
- CSharp
- C++
- VB
---

# ChannelLanguages Property

Gets the channel languages.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelLanguages As ReadOnlyCollection(Of ChannelLanguage)
    Get
    Set
'Usage
Dim instance As Channel
Dim value As ReadOnlyCollection(Of ChannelLanguage)

value = instance.ChannelLanguages

instance.ChannelLanguages = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ChannelLanguage> ChannelLanguages { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ChannelLanguage^>^ ChannelLanguages {
    ReadOnlyCollection<ChannelLanguage^>^ get ();
    void set (ReadOnlyCollection<ChannelLanguage^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ChannelLanguage](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The channel languages.  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

