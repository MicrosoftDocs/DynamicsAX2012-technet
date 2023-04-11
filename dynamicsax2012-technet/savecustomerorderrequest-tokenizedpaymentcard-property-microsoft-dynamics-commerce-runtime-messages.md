---
title: SaveCustomerOrderRequest.TokenizedPaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TokenizedPaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.TokenizedPaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.tokenizedpaymentcard(v=AX.60)
ms:contentKeyID: 65321275
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.TokenizedPaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# TokenizedPaymentCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TokenizedPaymentCard As TokenizedPaymentCard
    Get
    Private Set
'Usage
Dim instance As SaveCustomerOrderRequest
Dim value As TokenizedPaymentCard

value = instance.TokenizedPaymentCard
```

``` csharp
[DataMemberAttribute]
public TokenizedPaymentCard TokenizedPaymentCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TokenizedPaymentCard^ TokenizedPaymentCard {
    TokenizedPaymentCard^ get ();
    private: void set (TokenizedPaymentCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

