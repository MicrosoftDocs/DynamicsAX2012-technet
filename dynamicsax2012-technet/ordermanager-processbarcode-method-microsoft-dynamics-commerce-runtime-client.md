---
title: OrderManager.ProcessBarcode Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ProcessBarcode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.ProcessBarcode(System.String,System.String,System.Nullable{System.Decimal})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.processbarcode(v=AX.60)
ms:contentKeyID: 65322067
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.ProcessBarcode
dev_langs:
- CSharp
- C++
- VB
---

# ProcessBarcode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function ProcessBarcode ( _
    cartId As String, _
    barcode As String, _
    quantity As Nullable(Of Decimal) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim barcode As String
Dim quantity As Nullable(Of Decimal)
Dim returnValue As Cart

returnValue = instance.ProcessBarcode(cartId, _
    barcode, quantity)
```

``` csharp
public Cart ProcessBarcode(
    string cartId,
    string barcode,
    Nullable<decimal> quantity
)
```

``` c++
public:
Cart^ ProcessBarcode(
    String^ cartId, 
    String^ barcode, 
    Nullable<Decimal> quantity
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

