---
title: OrderManager.CreateOrTransferCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateOrTransferCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreateOrTransferCart(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.createortransfercart(v=AX.60)
ms:contentKeyID: 65319096
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreateOrTransferCart
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrTransferCart Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CreateOrTransferCart ( _
    cart As Cart _
) As Cart
'Usage
Dim instance As OrderManager
Dim cart As Cart
Dim returnValue As Cart

returnValue = instance.CreateOrTransferCart(cart)
```

``` csharp
public Cart CreateOrTransferCart(
    Cart cart
)
```

``` c++
public:
Cart^ CreateOrTransferCart(
    Cart^ cart
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

