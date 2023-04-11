---
title: GetLocalizedStringsRequest.TextId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TextId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsRequest.TextId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlocalizedstringsrequest.textid(v=AX.60)
ms:contentKeyID: 62211239
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsRequest.TextId
dev_langs:
- CSharp
- C++
- VB
---

# TextId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the text identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TextId As Nullable(Of Integer)
    Get
    Set
'Usage
Dim instance As GetLocalizedStringsRequest
Dim value As Nullable(Of Integer)

value = instance.TextId

instance.TextId = value
```

``` csharp
[DataMemberAttribute]
public Nullable<int> TextId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<int> TextId {
    Nullable<int> get ();
    void set (Nullable<int> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[GetLocalizedStringsRequest Class](getlocalizedstringsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

