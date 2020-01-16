---
title: GetDeliveryOptionsRequest Constructor (String, String, ICollection(String), Boolean, Address) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetDeliveryOptionsRequest Constructor (String, String, ICollection(String), Boolean, Address)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.#ctor(System.String,System.String,System.Collections.Generic.ICollection{System.String},System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsrequest.getdeliveryoptionsrequest(v=AX.60)
ms:contentKeyID: 62211177
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeliveryOptionsRequest Constructor (String, String, ICollection(String), Boolean, Address)

Initializes a new instance of the [GetDeliveryOptionsRequest](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    customerAccountNumber As String, _
    cartLineIds As ICollection(Of String), _
    fetchDeliveryOptionsForLines As Boolean, _
    shippingAddress As Address _
)
'Usage
Dim cartId As String
Dim customerAccountNumber As String
Dim cartLineIds As ICollection(Of String)
Dim fetchDeliveryOptionsForLines As Boolean
Dim shippingAddress As Address

Dim instance As New GetDeliveryOptionsRequest(cartId, _
    customerAccountNumber, cartLineIds, _
    fetchDeliveryOptionsForLines, shippingAddress)
```

``` csharp
public GetDeliveryOptionsRequest(
    string cartId,
    string customerAccountNumber,
    ICollection<string> cartLineIds,
    bool fetchDeliveryOptionsForLines,
    Address shippingAddress
)
```

``` c++
public:
GetDeliveryOptionsRequest(
    String^ cartId, 
    String^ customerAccountNumber, 
    ICollection<String^>^ cartLineIds, 
    bool fetchDeliveryOptionsForLines, 
    Address^ shippingAddress
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLineIds  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - fetchDeliveryOptionsForLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - shippingAddress  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDeliveryOptionsRequest Class](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetDeliveryOptionsRequest Overload](getdeliveryoptionsrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

