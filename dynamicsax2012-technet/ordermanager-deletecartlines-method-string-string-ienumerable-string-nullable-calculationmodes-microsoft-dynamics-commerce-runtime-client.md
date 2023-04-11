---
title: OrderManager.DeleteCartLines Method (String, String, IEnumerable(String), Nullable(CalculationModes)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DeleteCartLines Method (String, String, IEnumerable(String), Nullable(CalculationModes))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.DeleteCartLines(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.deletecartlines(v=AX.60)
ms:contentKeyID: 62215061
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeleteCartLines Method (String, String, IEnumerable(String), Nullable(CalculationModes))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Removes the specified items from the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function DeleteCartLines ( _
    cartId As String, _
    customerAccountNumber As String, _
    lineIds As IEnumerable(Of String), _
    modes As Nullable(Of CalculationModes) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim lineIds As IEnumerable(Of String)
Dim modes As Nullable(Of CalculationModes)
Dim returnValue As Cart

returnValue = instance.DeleteCartLines(cartId, _
    customerAccountNumber, lineIds, _
    modes)
```

``` csharp
public Cart DeleteCartLines(
    string cartId,
    string customerAccountNumber,
    IEnumerable<string> lineIds,
    Nullable<CalculationModes> modes
)
```

``` c++
public:
Cart^ DeleteCartLines(
    String^ cartId, 
    String^ customerAccountNumber, 
    IEnumerable<String^>^ lineIds, 
    Nullable<CalculationModes> modes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lineIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - modes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[DeleteCartLines Overload](ordermanager-deletecartlines-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

