---
title: OrderManager.VoidCartLines Method (String, IEnumerable(CartLine), Nullable(CalculationModes)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: VoidCartLines Method (String, IEnumerable(CartLine), Nullable(CalculationModes))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidCartLines(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine},System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.voidcartlines(v=AX.60)
ms:contentKeyID: 62212982
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VoidCartLines Method (String, IEnumerable(CartLine), Nullable(CalculationModes))

Voids the cart lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function VoidCartLines ( _
    cartId As String, _
    cartLines As IEnumerable(Of CartLine), _
    calculationModes As Nullable(Of CalculationModes) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim cartLines As IEnumerable(Of CartLine)
Dim calculationModes As Nullable(Of CalculationModes)
Dim returnValue As Cart

returnValue = instance.VoidCartLines(cartId, _
    cartLines, calculationModes)
```

``` csharp
public Cart VoidCartLines(
    string cartId,
    IEnumerable<CartLine> cartLines,
    Nullable<CalculationModes> calculationModes
)
```

``` c++
public:
Cart^ VoidCartLines(
    String^ cartId, 
    IEnumerable<CartLine^>^ cartLines, 
    Nullable<CalculationModes> calculationModes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - calculationModes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>If cart, cartLines are null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[VoidCartLines Overload](ordermanager-voidcartlines-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

