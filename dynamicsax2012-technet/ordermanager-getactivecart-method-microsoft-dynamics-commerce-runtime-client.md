---
title: OrderManager.GetActiveCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetActiveCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetActiveCart(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getactivecart(v=AX.60)
ms:contentKeyID: 62209339
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetActiveCart
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the latest shopping cart associated with the current user with the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetActiveCart ( _
    customerAccountNumber As String, _
    modes As CalculationModes _
) As Cart
'Usage
Dim instance As OrderManager
Dim customerAccountNumber As String
Dim modes As CalculationModes
Dim returnValue As Cart

returnValue = instance.GetActiveCart(customerAccountNumber, _
    modes)
```

``` csharp
public Cart GetActiveCart(
    string customerAccountNumber,
    CalculationModes modes
)
```

``` c++
public:
Cart^ GetActiveCart(
    String^ customerAccountNumber, 
    CalculationModes modes
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - modes  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The latest shopping cart of the customer for the current channel.[Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

