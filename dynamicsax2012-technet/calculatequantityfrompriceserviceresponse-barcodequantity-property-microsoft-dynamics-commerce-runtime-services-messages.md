---
title: CalculateQuantityFromPriceServiceResponse.BarcodeQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: BarcodeQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceResponse.BarcodeQuantity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.calculatequantityfrompriceserviceresponse.barcodequantity(v=AX.60)
ms:contentKeyID: 62212999
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceResponse.BarcodeQuantity
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeQuantity Property

Gets the Barcode quantity value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BarcodeQuantity As Decimal
    Get
    Private Set
'Usage
Dim instance As CalculateQuantityFromPriceServiceResponse
Dim value As Decimal

value = instance.BarcodeQuantity
```

``` csharp
[DataMemberAttribute]
public decimal BarcodeQuantity { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal BarcodeQuantity {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CalculateQuantityFromPriceServiceResponse Class](calculatequantityfrompriceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

