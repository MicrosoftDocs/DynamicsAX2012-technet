---
title: GetChannelProductAttributesResponse.ChannelProductAttributes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelProductAttributes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesResponse.ChannelProductAttributes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelproductattributesresponse.channelproductattributes(v=AX.60)
ms:contentKeyID: 49844510
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesResponse.ChannelProductAttributes
dev_langs:
- CSharp
- C++
- VB
---

# ChannelProductAttributes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel product attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelProductAttributes As ReadOnlyCollection(Of AttributeProduct)
    Get
    Private Set
'Usage
Dim instance As GetChannelProductAttributesResponse
Dim value As ReadOnlyCollection(Of AttributeProduct)

value = instance.ChannelProductAttributes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<AttributeProduct> ChannelProductAttributes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<AttributeProduct^>^ ChannelProductAttributes {
    ReadOnlyCollection<AttributeProduct^>^ get ();
    private: void set (ReadOnlyCollection<AttributeProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelProductAttributesResponse Class](getchannelproductattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

