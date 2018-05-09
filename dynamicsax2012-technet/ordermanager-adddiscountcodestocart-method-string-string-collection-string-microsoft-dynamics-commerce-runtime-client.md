---
title: OrderManager.AddDiscountCodesToCart Method (String, String, Collection(String)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddDiscountCodesToCart Method (String, String, Collection(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.AddDiscountCodesToCart(System.String,System.String,System.Collections.ObjectModel.Collection{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.adddiscountcodestocart(v=AX.60)
ms:contentKeyID: 65321624
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddDiscountCodesToCart Method (String, String, Collection(String))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddDiscountCodesToCart ( _
    cartId As String, _
    customerAccountNumber As String, _
    discountCodes As Collection(Of String) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim discountCodes As Collection(Of String)
Dim returnValue As Cart

returnValue = instance.AddDiscountCodesToCart(cartId, _
    customerAccountNumber, discountCodes)
```

``` csharp
public Cart AddDiscountCodesToCart(
    string cartId,
    string customerAccountNumber,
    Collection<string> discountCodes
)
```

``` c++
public:
Cart^ AddDiscountCodesToCart(
    String^ cartId, 
    String^ customerAccountNumber, 
    Collection<String^>^ discountCodes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCodes  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[AddDiscountCodesToCart Overload](ordermanager-adddiscountcodestocart-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

