---
title: ListingPublishStatus.ChannelState Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelState Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ChannelState
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.channelstate(v=AX.60)
ms:contentKeyID: 62202114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ChannelState
dev_langs:
- CSharp
- C++
- VB
---

# ChannelState Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the channel state.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELSTATE")> _
Public Property ChannelState As String
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As String

value = instance.ChannelState

instance.ChannelState = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELSTATE")]
public string ChannelState { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELSTATE")]
public:
property String^ ChannelState {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

