---
title: GetProductBarcodeDataResponse.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductBarcodeDataResponse.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductbarcodedataresponse.barcode(v=AX.60)
ms:contentKeyID: 65321027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductBarcodeDataResponse.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the ItemBarcode value for this response.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Barcode As ItemBarcode
    Get
    Private Set
'Usage
Dim instance As GetProductBarcodeDataResponse
Dim value As ItemBarcode

value = instance.Barcode
```

``` csharp
public ItemBarcode Barcode { get; private set; }
```

``` c++
public:
property ItemBarcode^ Barcode {
    ItemBarcode^ get ();
    private: void set (ItemBarcode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetProductBarcodeDataResponse Class](getproductbarcodedataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

