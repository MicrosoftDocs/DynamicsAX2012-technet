---
title: SaveCartRequest Constructor (Cart, TransactionOperationType) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveCartRequest Constructor (Cart, TransactionOperationType)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.savecartrequest(v=AX.60)
ms:contentKeyID: 62202436
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCartRequest Constructor (Cart, TransactionOperationType)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cart As Cart, _
    operationType As TransactionOperationType _
)
'Usage
Dim cart As Cart
Dim operationType As TransactionOperationType

Dim instance As New SaveCartRequest(cart, operationType)
```

``` csharp
public SaveCartRequest(
    Cart cart,
    TransactionOperationType operationType
)
```

``` c++
public:
SaveCartRequest(
    Cart^ cart, 
    TransactionOperationType operationType
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - operationType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType](transactionoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveCartRequest Overload](savecartrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

