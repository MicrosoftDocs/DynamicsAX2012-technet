---
title: ProcessBarcodeTypeRequest.CartId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest.CartId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.processbarcodetyperequest.cartid(v=AX.60)
ms:contentKeyID: 62207237
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest.CartId
dev_langs:
- CSharp
- C++
- VB
---

# CartId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartId As String
    Get
    Set
'Usage
Dim instance As ProcessBarcodeTypeRequest
Dim value As String

value = instance.CartId

instance.CartId = value
```

``` csharp
[DataMemberAttribute]
public string CartId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CartId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProcessBarcodeTypeRequest Class](processbarcodetyperequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

