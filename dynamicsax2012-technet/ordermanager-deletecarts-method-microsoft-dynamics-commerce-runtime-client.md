---
title: OrderManager.DeleteCarts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DeleteCarts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.DeleteCarts(System.String,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.deletecarts(v=AX.60)
ms:contentKeyID: 49831001
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.DeleteCarts
dev_langs:
- CSharp
- C++
- VB
---

# DeleteCarts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the carts associated with given identifiers and the current user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteCarts ( _
    customerAccountNumber As String, _
    cartIds As IEnumerable(Of String) _
)
'Usage
Dim instance As OrderManager
Dim customerAccountNumber As String
Dim cartIds As IEnumerable(Of String)

instance.DeleteCarts(customerAccountNumber, _
    cartIds)
```

``` csharp
public void DeleteCarts(
    string customerAccountNumber,
    IEnumerable<string> cartIds
)
```

``` c++
public:
void DeleteCarts(
    String^ customerAccountNumber, 
    IEnumerable<String^>^ cartIds
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

