---
title: GetDeliveryOptionsRequest.CartLineIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartLineIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.CartLineIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsrequest.cartlineids(v=AX.60)
ms:contentKeyID: 62206579
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.CartLineIds
dev_langs:
- CSharp
- C++
- VB
---

# CartLineIds Property

Gets a collection indicating the cart lines to get the delivery modes for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartLineIds As ICollection(Of String)
    Get
    Private Set
'Usage
Dim instance As GetDeliveryOptionsRequest
Dim value As ICollection(Of String)

value = instance.CartLineIds
```

``` csharp
[DataMemberAttribute]
public ICollection<string> CartLineIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<String^>^ CartLineIds {
    ICollection<String^>^ get ();
    private: void set (ICollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## Remarks

This is only considered if \[\!Malformed\!\] is true.

If \[\!Malformed\!\] is true and this property is not provided, all cart lines will be used.

## See Also

#### Reference

[GetDeliveryOptionsRequest Class](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

