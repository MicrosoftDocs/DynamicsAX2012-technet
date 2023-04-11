---
title: AddToGiftCardServiceRequest Constructor (String, Decimal, String, String, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AddToGiftCardServiceRequest Constructor (String, Decimal, String, String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.#ctor(System.String,System.Decimal,System.String,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.addtogiftcardservicerequest.addtogiftcardservicerequest(v=AX.60)
ms:contentKeyID: 65322014
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddToGiftCardServiceRequest Constructor (String, Decimal, String, String, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    giftCardId As String, _
    amount As Decimal, _
    currencyCode As String, _
    cardCurrencyCode As String, _
    transactionId As String, _
    isReversal As Boolean _
)
'Usage
Dim giftCardId As String
Dim amount As Decimal
Dim currencyCode As String
Dim cardCurrencyCode As String
Dim transactionId As String
Dim isReversal As Boolean

Dim instance As New AddToGiftCardServiceRequest(giftCardId, _
    amount, currencyCode, cardCurrencyCode, _
    transactionId, isReversal)
```

``` csharp
public AddToGiftCardServiceRequest(
    string giftCardId,
    decimal amount,
    string currencyCode,
    string cardCurrencyCode,
    string transactionId,
    bool isReversal
)
```

``` c++
public:
AddToGiftCardServiceRequest(
    String^ giftCardId, 
    Decimal amount, 
    String^ currencyCode, 
    String^ cardCurrencyCode, 
    String^ transactionId, 
    bool isReversal
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

  - cardCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isReversal  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AddToGiftCardServiceRequest Class](addtogiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[AddToGiftCardServiceRequest Overload](addtogiftcardservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

