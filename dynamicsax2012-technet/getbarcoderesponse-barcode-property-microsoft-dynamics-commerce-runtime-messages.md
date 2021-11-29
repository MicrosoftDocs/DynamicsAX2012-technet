---
title: GetBarcodeResponse.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeResponse.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbarcoderesponse.barcode(v=AX.60)
ms:contentKeyID: 62209713
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeResponse.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcode As Barcode
    Get
    Private Set
'Usage
Dim instance As GetBarcodeResponse
Dim value As Barcode

value = instance.Barcode
```

``` csharp
[DataMemberAttribute]
public Barcode Barcode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Barcode^ Barcode {
    Barcode^ get ();
    private: void set (Barcode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Barcode](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetBarcodeResponse Class](getbarcoderesponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

