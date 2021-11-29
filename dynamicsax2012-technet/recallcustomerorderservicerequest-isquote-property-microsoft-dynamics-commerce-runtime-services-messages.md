---
title: RecallCustomerOrderServiceRequest.IsQuote Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsQuote Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RecallCustomerOrderServiceRequest.IsQuote
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.recallcustomerorderservicerequest.isquote(v=AX.60)
ms:contentKeyID: 62204566
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RecallCustomerOrderServiceRequest.IsQuote
dev_langs:
- CSharp
- C++
- VB
---

# IsQuote Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to search for quotes or normal orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property IsQuote As Boolean
    Get
    Private Set
'Usage
Dim instance As RecallCustomerOrderServiceRequest
Dim value As Boolean

value = instance.IsQuote
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public bool IsQuote { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
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

[RecallCustomerOrderServiceRequest Class](recallcustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

