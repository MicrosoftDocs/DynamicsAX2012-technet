---
title: RecallCustomerOrderRequest.IsQuote Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsQuote Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.RecallCustomerOrderRequest.IsQuote
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.recallcustomerorderrequest.isquote(v=AX.60)
ms:contentKeyID: 62210659
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.RecallCustomerOrderRequest.IsQuote
dev_langs:
- CSharp
- C++
- VB
---

# IsQuote Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to search for quotes or normal orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsQuote As Boolean
    Get
    Private Set
'Usage
Dim instance As RecallCustomerOrderRequest
Dim value As Boolean

value = instance.IsQuote
```

``` csharp
[DataMemberAttribute]
public bool IsQuote { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsQuote {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[RecallCustomerOrderRequest Class](recallcustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

