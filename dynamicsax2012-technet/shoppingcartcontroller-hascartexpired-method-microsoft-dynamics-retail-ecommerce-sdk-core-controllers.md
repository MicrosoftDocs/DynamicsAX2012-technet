---
title: ShoppingCartController.HasCartExpired Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: HasCartExpired Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.HasCartExpired(System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.hascartexpired(v=AX.60)
ms:contentKeyID: 65318422
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.HasCartExpired
dev_langs:
- CSharp
- C++
- VB
---

# HasCartExpired Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function HasCartExpired ( _
    cartLastModifiedDate As DateTime _
) As Boolean
'Usage
Dim cartLastModifiedDate As DateTime
Dim returnValue As Boolean

returnValue = Me.HasCartExpired(cartLastModifiedDate)
```

``` csharp
protected virtual bool HasCartExpired(
    DateTime cartLastModifiedDate
)
```

``` c++
protected:
virtual bool HasCartExpired(
    DateTime cartLastModifiedDate
)
```

#### Parameters

  - cartLastModifiedDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

