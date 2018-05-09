---
title: GetChannelProductAttributesResponse Constructor (IEnumerable(AttributeProduct)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelProductAttributesResponse Constructor (IEnumerable(AttributeProduct))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelproductattributesresponse.getchannelproductattributesresponse(v=AX.60)
ms:contentKeyID: 49852866
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelProductAttributesResponse Constructor (IEnumerable(AttributeProduct))

Initializes a new instance of the [GetChannelProductAttributesResponse](getchannelproductattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    attributes As IEnumerable(Of AttributeProduct) _
)
'Usage
Dim attributes As IEnumerable(Of AttributeProduct)

Dim instance As New GetChannelProductAttributesResponse(attributes)
```

``` csharp
public GetChannelProductAttributesResponse(
    IEnumerable<AttributeProduct> attributes
)
```

``` c++
public:
GetChannelProductAttributesResponse(
    IEnumerable<AttributeProduct^>^ attributes
)
```

#### Parameters

  - attributes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelProductAttributesResponse Class](getchannelproductattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelProductAttributesResponse Overload](getchannelproductattributesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

