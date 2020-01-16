---
title: GetChannelAttributesResponse.ChannelAttributes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelAttributes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelAttributesResponse.ChannelAttributes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelattributesresponse.channelattributes(v=AX.60)
ms:contentKeyID: 49847439
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelAttributesResponse.ChannelAttributes
dev_langs:
- CSharp
- C++
- VB
---

# ChannelAttributes Property

Gets the channel attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelAttributes As ReadOnlyCollection(Of ChannelAttribute)
    Get
    Private Set
'Usage
Dim instance As GetChannelAttributesResponse
Dim value As ReadOnlyCollection(Of ChannelAttribute)

value = instance.ChannelAttributes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ChannelAttribute> ChannelAttributes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ChannelAttribute^>^ ChannelAttributes {
    ReadOnlyCollection<ChannelAttribute^>^ get ();
    private: void set (ReadOnlyCollection<ChannelAttribute^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelAttribute](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelAttributesResponse Class](getchannelattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

