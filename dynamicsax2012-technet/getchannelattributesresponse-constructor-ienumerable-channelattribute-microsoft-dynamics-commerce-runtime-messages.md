---
title: GetChannelAttributesResponse Constructor (IEnumerable(ChannelAttribute)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelAttributesResponse Constructor (IEnumerable(ChannelAttribute))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelAttributesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttribute})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelattributesresponse.getchannelattributesresponse(v=AX.60)
ms:contentKeyID: 49839094
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelAttributesResponse Constructor (IEnumerable(ChannelAttribute))

Initializes a new instance of the [GetChannelAttributesResponse](getchannelattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    attributes As IEnumerable(Of ChannelAttribute) _
)
'Usage
Dim attributes As IEnumerable(Of ChannelAttribute)

Dim instance As New GetChannelAttributesResponse(attributes)
```

``` csharp
public GetChannelAttributesResponse(
    IEnumerable<ChannelAttribute> attributes
)
```

``` c++
public:
GetChannelAttributesResponse(
    IEnumerable<ChannelAttribute^>^ attributes
)
```

#### Parameters

  - attributes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ChannelAttribute](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelAttributesResponse Class](getchannelattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelAttributesResponse Overload](getchannelattributesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

