---
title: GetItemBarcodesByIdRequest Constructor (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemBarcodesByIdRequest Constructor (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitembarcodesbyidrequest.getitembarcodesbyidrequest(v=AX.60)
ms:contentKeyID: 62209117
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemBarcodesByIdRequest Constructor (IEnumerable(String))

Initializes a new instance of the [GetItemBarcodesByIdRequest](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemIds As IEnumerable(Of String) _
)
'Usage
Dim itemIds As IEnumerable(Of String)

Dim instance As New GetItemBarcodesByIdRequest(itemIds)
```

``` csharp
public GetItemBarcodesByIdRequest(
    IEnumerable<string> itemIds
)
```

``` c++
public:
GetItemBarcodesByIdRequest(
    IEnumerable<String^>^ itemIds
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetItemBarcodesByIdRequest Class](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemBarcodesByIdRequest Overload](getitembarcodesbyidrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

