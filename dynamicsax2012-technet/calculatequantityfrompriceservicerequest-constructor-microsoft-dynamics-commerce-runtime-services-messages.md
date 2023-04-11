---
title: CalculateQuantityFromPriceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateQuantityFromPriceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest.#ctor(System.Decimal,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatequantityfrompriceservicerequest.calculatequantityfrompriceservicerequest(v=AX.60)
ms:contentKeyID: 65321025
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CalculateQuantityFromPriceServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    barcodePrice As Decimal, _
    defaultProductPrice As Decimal, _
    unitOfMeasure As String _
)
'Usage
Dim barcodePrice As Decimal
Dim defaultProductPrice As Decimal
Dim unitOfMeasure As String

Dim instance As New CalculateQuantityFromPriceServiceRequest(barcodePrice, _
    defaultProductPrice, unitOfMeasure)
```

``` csharp
public CalculateQuantityFromPriceServiceRequest(
    decimal barcodePrice,
    decimal defaultProductPrice,
    string unitOfMeasure
)
```

``` c++
public:
CalculateQuantityFromPriceServiceRequest(
    Decimal barcodePrice, 
    Decimal defaultProductPrice, 
    String^ unitOfMeasure
)
```

#### Parameters

  - barcodePrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - defaultProductPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CalculateQuantityFromPriceServiceRequest Class](calculatequantityfrompriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

