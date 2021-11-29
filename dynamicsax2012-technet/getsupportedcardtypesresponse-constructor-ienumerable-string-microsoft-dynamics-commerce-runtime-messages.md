---
title: GetSupportedCardTypesResponse Constructor (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetSupportedCardTypesResponse Constructor (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedCardTypesResponse.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getsupportedcardtypesresponse.getsupportedcardtypesresponse(v=AX.60)
ms:contentKeyID: 49846688
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSupportedCardTypesResponse Constructor (IEnumerable(String))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetSupportedCardTypesResponse](getsupportedcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cardTypes As IEnumerable(Of String) _
)
'Usage
Dim cardTypes As IEnumerable(Of String)

Dim instance As New GetSupportedCardTypesResponse(cardTypes)
```

``` csharp
public GetSupportedCardTypesResponse(
    IEnumerable<string> cardTypes
)
```

``` c++
public:
GetSupportedCardTypesResponse(
    IEnumerable<String^>^ cardTypes
)
```

#### Parameters

  - cardTypes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetSupportedCardTypesResponse Class](getsupportedcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetSupportedCardTypesResponse Overload](getsupportedcardtypesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

