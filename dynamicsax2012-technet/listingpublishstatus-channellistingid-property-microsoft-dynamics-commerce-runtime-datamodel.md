---
title: ListingPublishStatus.ChannelListingId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelListingId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ChannelListingId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.channellistingid(v=AX.60)
ms:contentKeyID: 49824330
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.ChannelListingId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelListingId Property

Gets or sets the channel listing identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELLISTINGID")> _
Public Property ChannelListingId As String
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As String

value = instance.ChannelListingId

instance.ChannelListingId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELLISTINGID")]
public string ChannelListingId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELLISTINGID")]
public:
property String^ ChannelListingId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

