---
title: IssueOrAddToGiftCardRequest Constructor (String, String, Decimal, String, Boolean, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IssueOrAddToGiftCardRequest Constructor (String, String, Decimal, String, Boolean, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.#ctor(System.String,System.String,System.Decimal,System.String,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.issueoraddtogiftcardrequest.issueoraddtogiftcardrequest(v=AX.60)
ms:contentKeyID: 65322598
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IssueOrAddToGiftCardRequest Constructor (String, String, Decimal, String, Boolean, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    giftCardId As String, _
    amount As Decimal, _
    currencyCode As String, _
    existingGiftCard As Boolean, _
    lineDescription As String _
)
'Usage
Dim cartId As String
Dim giftCardId As String
Dim amount As Decimal
Dim currencyCode As String
Dim existingGiftCard As Boolean
Dim lineDescription As String

Dim instance As New IssueOrAddToGiftCardRequest(cartId, _
    giftCardId, amount, currencyCode, _
    existingGiftCard, lineDescription)
```

``` csharp
public IssueOrAddToGiftCardRequest(
    string cartId,
    string giftCardId,
    decimal amount,
    string currencyCode,
    bool existingGiftCard,
    string lineDescription
)
```

``` c++
public:
IssueOrAddToGiftCardRequest(
    String^ cartId, 
    String^ giftCardId, 
    Decimal amount, 
    String^ currencyCode, 
    bool existingGiftCard, 
    String^ lineDescription
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - existingGiftCard  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - lineDescription  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IssueOrAddToGiftCardRequest Class](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[IssueOrAddToGiftCardRequest Overload](issueoraddtogiftcardrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

