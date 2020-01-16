---
title: GetItemBarcodesByIdResponse.Barcodes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Barcodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdResponse.Barcodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitembarcodesbyidresponse.barcodes(v=AX.60)
ms:contentKeyID: 62208273
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdResponse.Barcodes
dev_langs:
- CSharp
- C++
- VB
---

# Barcodes Property

Gets the collection of barcodes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcodes As ReadOnlyCollection(Of ItemBarcode)
    Get
    Private Set
'Usage
Dim instance As GetItemBarcodesByIdResponse
Dim value As ReadOnlyCollection(Of ItemBarcode)

value = instance.Barcodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ItemBarcode> Barcodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ItemBarcode^>^ Barcodes {
    ReadOnlyCollection<ItemBarcode^>^ get ();
    private: void set (ReadOnlyCollection<ItemBarcode^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemBarcodesByIdResponse Class](getitembarcodesbyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

