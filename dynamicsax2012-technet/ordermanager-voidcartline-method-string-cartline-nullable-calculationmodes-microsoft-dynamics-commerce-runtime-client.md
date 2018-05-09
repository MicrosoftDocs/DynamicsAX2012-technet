---
title: OrderManager.VoidCartLine Method (String, CartLine, Nullable(CalculationModes)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: VoidCartLine Method (String, CartLine, Nullable(CalculationModes))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidCartLine(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.voidcartline(v=AX.60)
ms:contentKeyID: 62215165
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VoidCartLine Method (String, CartLine, Nullable(CalculationModes))

Voids the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function VoidCartLine ( _
    cartId As String, _
    cartLine As CartLine, _
    calculationModes As Nullable(Of CalculationModes) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim cartLine As CartLine
Dim calculationModes As Nullable(Of CalculationModes)
Dim returnValue As Cart

returnValue = instance.VoidCartLine(cartId, _
    cartLine, calculationModes)
```

``` csharp
public Cart VoidCartLine(
    string cartId,
    CartLine cartLine,
    Nullable<CalculationModes> calculationModes
)
```

``` c++
public:
Cart^ VoidCartLine(
    String^ cartId, 
    CartLine^ cartLine, 
    Nullable<CalculationModes> calculationModes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - calculationModes  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[VoidCartLine Overload](ordermanager-voidcartline-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

