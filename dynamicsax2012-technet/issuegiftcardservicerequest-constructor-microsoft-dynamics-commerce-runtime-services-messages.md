---
title: IssueGiftCardServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IssueGiftCardServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.#ctor(System.String,System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issuegiftcardservicerequest.issuegiftcardservicerequest(v=AX.60)
ms:contentKeyID: 65319476
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# IssueGiftCardServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    id As String, _
    amount As Decimal, _
    currencyCode As String, _
    transactionId As String _
)
'Usage
Dim id As String
Dim amount As Decimal
Dim currencyCode As String
Dim transactionId As String

Dim instance As New IssueGiftCardServiceRequest(id, amount, _
    currencyCode, transactionId)
```

``` csharp
public IssueGiftCardServiceRequest(
    string id,
    decimal amount,
    string currencyCode,
    string transactionId
)
```

``` c++
public:
IssueGiftCardServiceRequest(
    String^ id, 
    Decimal amount, 
    String^ currencyCode, 
    String^ transactionId
)
```

#### Parameters

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IssueGiftCardServiceRequest Class](issuegiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

