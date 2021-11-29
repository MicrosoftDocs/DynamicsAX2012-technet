---
title: SaveCustomerOrderRequest.CardTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CardTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.CardTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.cardtypeid(v=AX.60)
ms:contentKeyID: 62209343
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.CardTypeId
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the payment card type ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypeId As String
    Get
    Private Set
'Usage
Dim instance As SaveCustomerOrderRequest
Dim value As String

value = instance.CardTypeId
```

``` csharp
[DataMemberAttribute]
public string CardTypeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardTypeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

