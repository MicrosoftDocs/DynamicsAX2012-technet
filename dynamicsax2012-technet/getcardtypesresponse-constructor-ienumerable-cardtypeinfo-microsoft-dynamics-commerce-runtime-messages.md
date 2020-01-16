---
title: GetCardTypesResponse Constructor (IEnumerable(CardTypeInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCardTypesResponse Constructor (IEnumerable(CardTypeInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcardtypesresponse.getcardtypesresponse(v=AX.60)
ms:contentKeyID: 62208101
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypesResponse Constructor (IEnumerable(CardTypeInfo))

Initializes a new instance of the [GetCardTypesResponse](getcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cardTypes As IEnumerable(Of CardTypeInfo) _
)
'Usage
Dim cardTypes As IEnumerable(Of CardTypeInfo)

Dim instance As New GetCardTypesResponse(cardTypes)
```

``` csharp
public GetCardTypesResponse(
    IEnumerable<CardTypeInfo> cardTypes
)
```

``` c++
public:
GetCardTypesResponse(
    IEnumerable<CardTypeInfo^>^ cardTypes
)
```

#### Parameters

  - cardTypes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCardTypesResponse Class](getcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCardTypesResponse Overload](getcardtypesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

