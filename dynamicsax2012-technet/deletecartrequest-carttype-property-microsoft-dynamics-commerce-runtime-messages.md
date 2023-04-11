---
title: DeleteCartRequest.CartType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteCartRequest.CartType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletecartrequest.carttype(v=AX.60)
ms:contentKeyID: 62210148
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteCartRequest.CartType
dev_langs:
- CSharp
- C++
- VB
---

# CartType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart type associated with the given cart identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartType As CartType
    Get
    Set
'Usage
Dim instance As DeleteCartRequest
Dim value As CartType

value = instance.CartType

instance.CartType = value
```

``` csharp
[DataMemberAttribute]
public CartType CartType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CartType CartType {
    CartType get ();
    void set (CartType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType](carttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CartType](carttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DeleteCartRequest Class](deletecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

