---
title: CreateOrderFromCartRequest.CartTenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartTenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest.CartTenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createorderfromcartrequest.carttenderlines(v=AX.60)
ms:contentKeyID: 62204938
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest.CartTenderLines
dev_langs:
- CSharp
- C++
- VB
---

# CartTenderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets collection of the CartTenderLines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartTenderLines As Collection(Of CartTenderLine)
    Get
    Private Set
'Usage
Dim instance As CreateOrderFromCartRequest
Dim value As Collection(Of CartTenderLine)

value = instance.CartTenderLines
```

``` csharp
[DataMemberAttribute]
public Collection<CartTenderLine> CartTenderLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<CartTenderLine^>^ CartTenderLines {
    Collection<CartTenderLine^>^ get ();
    private: void set (Collection<CartTenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CreateOrderFromCartRequest Class](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

