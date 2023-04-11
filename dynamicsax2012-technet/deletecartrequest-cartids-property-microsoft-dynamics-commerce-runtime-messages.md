---
title: DeleteCartRequest.CartIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteCartRequest.CartIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletecartrequest.cartids(v=AX.60)
ms:contentKeyID: 49852849
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteCartRequest.CartIds
dev_langs:
- CSharp
- C++
- VB
---

# CartIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of cart identifiers to delete.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartIds As Collection(Of String)
    Get
    Private Set
'Usage
Dim instance As DeleteCartRequest
Dim value As Collection(Of String)

value = instance.CartIds
```

``` csharp
[DataMemberAttribute]
public Collection<string> CartIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ CartIds {
    Collection<String^>^ get ();
    private: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[DeleteCartRequest Class](deletecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

