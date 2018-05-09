---
title: GetChannelCategoryAttributesResponse.ChannelCategoryAttributes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelCategoryAttributes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesResponse.ChannelCategoryAttributes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryattributesresponse.channelcategoryattributes(v=AX.60)
ms:contentKeyID: 49840377
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesResponse.ChannelCategoryAttributes
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCategoryAttributes Property

Gets the channel category attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelCategoryAttributes As ReadOnlyCollection(Of AttributeCategory)
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryAttributesResponse
Dim value As ReadOnlyCollection(Of AttributeCategory)

value = instance.ChannelCategoryAttributes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<AttributeCategory> ChannelCategoryAttributes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<AttributeCategory^>^ ChannelCategoryAttributes {
    ReadOnlyCollection<AttributeCategory^>^ get ();
    private: void set (ReadOnlyCollection<AttributeCategory^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryAttributesResponse Class](getchannelcategoryattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

