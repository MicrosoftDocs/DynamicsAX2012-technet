---
title: GetItemBarcodesByIdResponse Constructor (IEnumerable(ItemBarcode)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemBarcodesByIdResponse Constructor (IEnumerable(ItemBarcode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitembarcodesbyidresponse.getitembarcodesbyidresponse(v=AX.60)
ms:contentKeyID: 62211665
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemBarcodesByIdResponse Constructor (IEnumerable(ItemBarcode))

Initializes a new instance of the [GetItemBarcodesByIdResponse](getitembarcodesbyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    barcodes As IEnumerable(Of ItemBarcode) _
)
'Usage
Dim barcodes As IEnumerable(Of ItemBarcode)

Dim instance As New GetItemBarcodesByIdResponse(barcodes)
```

``` csharp
public GetItemBarcodesByIdResponse(
    IEnumerable<ItemBarcode> barcodes
)
```

``` c++
public:
GetItemBarcodesByIdResponse(
    IEnumerable<ItemBarcode^>^ barcodes
)
```

#### Parameters

  - barcodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemBarcodesByIdResponse Class](getitembarcodesbyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemBarcodesByIdResponse Overload](getitembarcodesbyidresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

