---
title: PriceCheckRequest Constructor (String, String, String, String, String, Decimal) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PriceCheckRequest Constructor (String, String, String, String, String, Decimal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckrequest.pricecheckrequest(v=AX.60)
ms:contentKeyID: 62214494
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PriceCheckRequest Constructor (String, String, String, String, String, Decimal)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PriceCheckRequest](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    inventDimId As String, _
    barcode As String, _
    customerAccountNumber As String, _
    unitOfMeasureSymbol As String, _
    quantity As Decimal _
)
'Usage
Dim itemId As String
Dim inventDimId As String
Dim barcode As String
Dim customerAccountNumber As String
Dim unitOfMeasureSymbol As String
Dim quantity As Decimal

Dim instance As New PriceCheckRequest(itemId, _
    inventDimId, barcode, customerAccountNumber, _
    unitOfMeasureSymbol, quantity)
```

``` csharp
public PriceCheckRequest(
    string itemId,
    string inventDimId,
    string barcode,
    string customerAccountNumber,
    string unitOfMeasureSymbol,
    decimal quantity
)
```

``` c++
public:
PriceCheckRequest(
    String^ itemId, 
    String^ inventDimId, 
    String^ barcode, 
    String^ customerAccountNumber, 
    String^ unitOfMeasureSymbol, 
    Decimal quantity
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasureSymbol  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[PriceCheckRequest Class](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[PriceCheckRequest Overload](pricecheckrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

