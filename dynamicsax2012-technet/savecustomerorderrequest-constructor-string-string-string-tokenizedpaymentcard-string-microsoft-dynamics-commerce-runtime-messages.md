---
title: SaveCustomerOrderRequest Constructor (String, String, String, TokenizedPaymentCard, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveCustomerOrderRequest Constructor (String, String, String, TokenizedPaymentCard, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.#ctor(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.savecustomerorderrequest(v=AX.60)
ms:contentKeyID: 65321595
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCustomerOrderRequest Constructor (String, String, String, TokenizedPaymentCard, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    receiptEmail As String, _
    receiptNumberSequence As String, _
    tokenizedPaymentCard As TokenizedPaymentCard, _
    cardTypeId As String _
)
'Usage
Dim cartId As String
Dim receiptEmail As String
Dim receiptNumberSequence As String
Dim tokenizedPaymentCard As TokenizedPaymentCard
Dim cardTypeId As String

Dim instance As New SaveCustomerOrderRequest(cartId, _
    receiptEmail, receiptNumberSequence, _
    tokenizedPaymentCard, cardTypeId)
```

``` csharp
public SaveCustomerOrderRequest(
    string cartId,
    string receiptEmail,
    string receiptNumberSequence,
    TokenizedPaymentCard tokenizedPaymentCard,
    string cardTypeId
)
```

``` c++
public:
SaveCustomerOrderRequest(
    String^ cartId, 
    String^ receiptEmail, 
    String^ receiptNumberSequence, 
    TokenizedPaymentCard^ tokenizedPaymentCard, 
    String^ cardTypeId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tokenizedPaymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveCustomerOrderRequest Overload](savecustomerorderrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

