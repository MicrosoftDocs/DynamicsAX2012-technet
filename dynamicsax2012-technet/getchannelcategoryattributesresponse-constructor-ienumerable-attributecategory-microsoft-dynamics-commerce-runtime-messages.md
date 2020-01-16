---
title: GetChannelCategoryAttributesResponse Constructor (IEnumerable(AttributeCategory)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelCategoryAttributesResponse Constructor (IEnumerable(AttributeCategory))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryattributesresponse.getchannelcategoryattributesresponse(v=AX.60)
ms:contentKeyID: 49856262
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCategoryAttributesResponse Constructor (IEnumerable(AttributeCategory))

Initializes a new instance of the [GetChannelCategoryAttributesResponse](getchannelcategoryattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    attributes As IEnumerable(Of AttributeCategory) _
)
'Usage
Dim attributes As IEnumerable(Of AttributeCategory)

Dim instance As New GetChannelCategoryAttributesResponse(attributes)
```

``` csharp
public GetChannelCategoryAttributesResponse(
    IEnumerable<AttributeCategory> attributes
)
```

``` c++
public:
GetChannelCategoryAttributesResponse(
    IEnumerable<AttributeCategory^>^ attributes
)
```

#### Parameters

  - attributes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelCategoryAttributesResponse Class](getchannelcategoryattributesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelCategoryAttributesResponse Overload](getchannelcategoryattributesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

