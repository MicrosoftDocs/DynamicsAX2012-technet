---
title: OrderManager.OverridePrice Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: OverridePrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.OverridePrice(System.String,System.String,System.Decimal,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.overrideprice(v=AX.60)
ms:contentKeyID: 62206727
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.OverridePrice
dev_langs:
- CSharp
- C++
- VB
---

# OverridePrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Apply price override to a cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function OverridePrice ( _
    cartId As String, _
    lineId As String, _
    newPrice As Decimal, _
    modes As Nullable(Of CalculationModes) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim lineId As String
Dim newPrice As Decimal
Dim modes As Nullable(Of CalculationModes)
Dim returnValue As Cart

returnValue = instance.OverridePrice(cartId, _
    lineId, newPrice, modes)
```

``` csharp
public Cart OverridePrice(
    string cartId,
    string lineId,
    decimal newPrice,
    Nullable<CalculationModes> modes
)
```

``` c++
public:
Cart^ OverridePrice(
    String^ cartId, 
    String^ lineId, 
    Decimal newPrice, 
    Nullable<CalculationModes> modes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - modes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The cart object.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

