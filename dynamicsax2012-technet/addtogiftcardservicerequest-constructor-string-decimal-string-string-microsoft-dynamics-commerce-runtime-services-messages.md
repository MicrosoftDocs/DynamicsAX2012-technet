---
title: AddToGiftCardServiceRequest Constructor (String, Decimal, String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AddToGiftCardServiceRequest Constructor (String, Decimal, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.#ctor(System.String,System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.addtogiftcardservicerequest.addtogiftcardservicerequest(v=AX.60)
ms:contentKeyID: 65322699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddToGiftCardServiceRequest Constructor (String, Decimal, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    giftCardId As String, _
    amount As Decimal, _
    currencyCode As String, _
    transactionId As String _
)
'Usage
Dim giftCardId As String
Dim amount As Decimal
Dim currencyCode As String
Dim transactionId As String

Dim instance As New AddToGiftCardServiceRequest(giftCardId, _
    amount, currencyCode, transactionId)
```

``` csharp
public AddToGiftCardServiceRequest(
    string giftCardId,
    decimal amount,
    string currencyCode,
    string transactionId
)
```

``` c++
public:
AddToGiftCardServiceRequest(
    String^ giftCardId, 
    Decimal amount, 
    String^ currencyCode, 
    String^ transactionId
)
```

#### Parameters

  - giftCardId  
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

[AddToGiftCardServiceRequest Class](addtogiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[AddToGiftCardServiceRequest Overload](addtogiftcardservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

