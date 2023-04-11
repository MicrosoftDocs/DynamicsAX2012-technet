---
title: SaveCartLinesRequest.CartLines Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartLinesRequest.CartLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartlinesrequest.cartlines(v=AX.60)
ms:contentKeyID: 62215246
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartLinesRequest.CartLines
dev_langs:
- CSharp
- C++
- VB
---

# CartLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CartLines As IEnumerable(Of CartLine)
    Get
    Set
'Usage
Dim instance As SaveCartLinesRequest
Dim value As IEnumerable(Of CartLine)

value = instance.CartLines

instance.CartLines = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public IEnumerable<CartLine> CartLines { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property IEnumerable<CartLine^>^ CartLines {
    IEnumerable<CartLine^>^ get ();
    void set (IEnumerable<CartLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SaveCartLinesRequest Class](savecartlinesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

