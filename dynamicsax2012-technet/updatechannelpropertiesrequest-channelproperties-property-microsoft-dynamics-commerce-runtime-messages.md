---
title: UpdateChannelPropertiesRequest.ChannelProperties Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPropertiesRequest.ChannelProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.updatechannelpropertiesrequest.channelproperties(v=AX.60)
ms:contentKeyID: 49846070
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPropertiesRequest.ChannelProperties
dev_langs:
- CSharp
- C++
- VB
---

# ChannelProperties Property

Gets or sets channel properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelProperties As IEnumerable(Of ChannelProperty)
    Get
    Set
'Usage
Dim instance As UpdateChannelPropertiesRequest
Dim value As IEnumerable(Of ChannelProperty)

value = instance.ChannelProperties

instance.ChannelProperties = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ChannelProperty> ChannelProperties { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ChannelProperty^>^ ChannelProperties {
    IEnumerable<ChannelProperty^>^ get ();
    void set (IEnumerable<ChannelProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ChannelProperty](channelproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[UpdateChannelPropertiesRequest Class](updatechannelpropertiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

