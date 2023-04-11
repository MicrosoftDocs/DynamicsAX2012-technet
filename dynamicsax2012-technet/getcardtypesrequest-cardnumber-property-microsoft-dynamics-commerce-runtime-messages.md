---
title: GetCardTypesRequest.CardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesRequest.CardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcardtypesrequest.cardnumber(v=AX.60)
ms:contentKeyID: 62210813
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesRequest.CardNumber
dev_langs:
- CSharp
- C++
- VB
---

# CardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card number to match card types against.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property CardNumber As String
    Get
    Set
'Usage
Dim instance As GetCardTypesRequest
Dim value As String

value = instance.CardNumber

instance.CardNumber = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string CardNumber { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ CardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetCardTypesRequest Class](getcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

